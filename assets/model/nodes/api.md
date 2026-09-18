# API

*API definition*

**What it is.** Defines an API endpoint's request and response contract directly — no locator involved.

{% hint style="info" %}
**Why it exists.** API verification compares structured data rather than interacting with a UI, so it runs entirely server-side with no script or keyword-engine dependency.
{% endhint %}

**Who uses it:** Backend / API test engineers, often before any UI flow exists

## Setting it up

{% stepper %}
{% step %}
Open Model → Application → API.
{% endstep %}
{% step %}
Add the endpoint's method, URL, and parameters.
{% endstep %}
{% step %}
Define the expected response schema.
{% endstep %}
{% step %}
Save — Design can build a Testcase directly against this contract, no locator needed.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/model-api.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how API connects to the rest of Application Model.

