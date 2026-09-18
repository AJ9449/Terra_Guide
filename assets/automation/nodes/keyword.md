# Keyword

*Reusable named action*

**What it is.** A named, reusable action — Input, Verify, Retrieve, File Fetch — applied explicitly in Web/Mobile steps.

{% hint style="info" %}
**Why it exists.** Without keywords, every test case would reimplement the same “type text” or “check text” logic. A keyword makes that write-once, and a fix propagates everywhere it is used.
{% endhint %}

**Who uses it:** Automation engineers building the shared vocabulary QA engineers pick from

## Setting it up

{% stepper %}
{% step %}
Open Automation → Folders → Keyword.
{% endstep %}
{% step %}
Choose the action type (Input, Verify, Retrieve, File Fetch).
{% endstep %}
{% step %}
Name it clearly so QA engineers can find it.
{% endstep %}
{% step %}
Save — it's now available inside any Web/Mobile Testcase step.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/automation-keyword.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how Keyword connects to the rest of Automation.

