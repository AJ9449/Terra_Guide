# Calc (CAL)

*Calculation / simulation node*

**What it is.** Computes an expected value from inputs — a discount, a converted amount, a computed tax.

{% hint style="info" %}
**Why it exists.** Some checks are not “does the field say X” but “does the field match this formula” — defining the formula once keeps every test that uses it consistent.
{% endhint %}

**Who uses it:** QA engineers testing pricing, billing, or other rule-driven logic

## Setting it up

{% stepper %}
{% step %}
Open Model → Application → Calc.
{% endstep %}
{% step %}
Define the inputs the formula needs.
{% endstep %}
{% step %}
Write the expected-value formula.
{% endstep %}
{% step %}
Save so Design can reference it inside a verification step.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/model-calc.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how Calc (CAL) connects to the rest of Application Model.

