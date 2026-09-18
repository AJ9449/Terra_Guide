# Test Design — End-to-end edge cases

Illustrative examples — sanity-check these against real product behavior before they go in front of a client.

## Checkout only fails when a coupon is applied after a cart change

{% stepper %}
{% step %}
Build each step (add to cart, modify cart, apply coupon, checkout) as its own Testcase.
{% endstep %}
{% step %}
Chain them into a Scenario with that exact ordering.
{% endstep %}
{% step %}
Run the Scenario — testing the steps in isolation would never catch this ordering bug.
{% endstep %}
{% endstepper %}

## Cross-environment regression before a release

{% stepper %}
{% step %}
Identify the Testcases that touch areas changed in this release.
{% endstep %}
{% step %}
Combine them into one Scenario scoped to the release.
{% endstep %}
{% step %}
Use per-flag controls to skip steps not touched by this cycle, then run across environments.
{% endstep %}
{% endstepper %}

