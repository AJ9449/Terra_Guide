# Formula

*Shared calculation logic*

**What it is.** Shared calculation logic, reusable across many unrelated test cases.

{% hint style="info" %}
**Why it exists.** Calculations like “is this within business hours” get reused often — defining one copy avoids different copies drifting apart over time.
{% endhint %}

**Who uses it:** Automation engineers standardizing logic used across multiple QA teams

## Setting it up

{% stepper %}
{% step %}
Open Automation → Folders → Formula.
{% endstep %}
{% step %}
Define the calculation once.
{% endstep %}
{% step %}
Reference it from every test case that needs it.
{% endstep %}
{% step %}
Update the one Formula when the underlying rule changes.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/automation-formula.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how Formula connects to the rest of Automation.

