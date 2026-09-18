# Application Model — End-to-end edge cases

Illustrative examples — sanity-check these against real product behavior before they go in front of a client.

## A payment API intermittently times out under load

{% stepper %}
{% step %}
Model the endpoint's contract with an API node.
{% endstep %}
{% step %}
Pair it with a Calc node to compute the expected retry/backoff timing.
{% endstep %}
{% step %}
Hand both to Design so the Testcase verifies correct retry behavior, not just pass/fail on one call.
{% endstep %}
{% endstepper %}

## A multi-organization billing statement needs verifying

{% stepper %}
{% step %}
Use a FOR node to generate claims across organizations with different billing rules.
{% endstep %}
{% step %}
Use a PDF node to verify the resulting statement's text against what FOR computed.
{% endstep %}
{% step %}
Re-run for each organization's rule set to confirm none produce a mismatched statement.
{% endstep %}
{% endstepper %}

