# FOR

*Billing / financial-record node*

**What it is.** Generates billing and financial records across organizations — medical claims, purchases, and similar record types.

{% hint style="info" %}
**Why it exists.** Financial record generation has to be modeled as a repeatable, parameterized process, since the same underlying logic runs differently per organization's rules.
{% endhint %}

**Who uses it:** QA engineers on billing- or claims-heavy TerrA deployments

## Setting it up

{% stepper %}
{% step %}
Open Model → Application → FOR.
{% endstep %}
{% step %}
Set up the organizations and their billing rules.
{% endstep %}
{% step %}
Define the record fields FOR should generate.
{% endstep %}
{% step %}
Save so Design can generate and verify records per organization.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/model-for.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how FOR connects to the rest of Application Model.

