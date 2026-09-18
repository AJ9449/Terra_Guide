# Scenario

*Conditional test-case grouping*

**What it is.** Groups existing test cases by conditional flow to represent one end-to-end business journey.

{% hint style="info" %}
**Why it exists.** Some defects only appear when steps happen in sequence with real dependencies between them — Scenario tests the journey, not just isolated steps.
{% endhint %}

**Who uses it:** QA leads and engineers responsible for release-level regression coverage

## Setting it up

{% stepper %}
{% step %}
Create a new Scenario node under a Region.
{% endstep %}
{% step %}
Import the Testcases that make up the journey.
{% endstep %}
{% step %}
Set per-flag controls for how each behaves inside the sequence.
{% endstep %}
{% step %}
Save and deploy like a standalone case.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/design-scenario.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how Scenario connects to the rest of Test Design.

