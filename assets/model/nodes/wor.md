# WOR

*Web Object Repository*

**What it is.** Stores element locators for a web application's UI.

{% hint style="info" %}
**Why it exists.** Centralizing locators means a UI change updates one repository entry instead of every test case that touches that element.
{% endhint %}

**Who uses it:** QA / Automation engineers, during initial project setup

## Setting it up

{% stepper %}
{% step %}
Open Model → Application → Web OR.
{% endstep %}
{% step %}
Launch the target web app from the recorder.
{% endstep %}
{% step %}
Capture each element you'll need and give it a readable name.
{% endstep %}
{% step %}
Save — it's now available to every Testcase under this Application.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/model-wor.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how WOR connects to the rest of Application Model.

