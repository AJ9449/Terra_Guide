# Automation — End-to-end edge cases

Illustrative examples — sanity-check these against real product behavior before they go in front of a client.

## A date picker behaves inconsistently across browsers

{% stepper %}
{% step %}
Confirm the standard Input keyword can't reliably select a date on the affected browser.
{% endstep %}
{% step %}
Write a Script that handles the widget's specific quirk.
{% endstep %}
{% step %}
Wrap the Script with the surrounding Verify keyword as a Flow.
{% endstep %}
{% step %}
Drop the Flow into the Testcase — QA never touches the script directly.
{% endstep %}
{% endstepper %}

## Standardizing “business hours” logic across 40 test cases

{% stepper %}
{% step %}
Define the time-zone-aware “business hours” check once, as a Formula.
{% endstep %}
{% step %}
Reference that Formula from every test case that needs it instead of re-implementing the check.
{% endstep %}
{% step %}
When the policy changes (e.g. extended hours), update the one Formula and every test case picks it up.
{% endstep %}
{% endstepper %}

