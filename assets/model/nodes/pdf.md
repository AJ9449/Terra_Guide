# PDF

*PDF verification node*

**What it is.** Verifies text or image content inside a generated PDF document.

{% hint style="info" %}
**Why it exists.** PDFs are common outputs for invoices, statements, and reports, and verifying a rendered document needs different handling than verifying a live UI.
{% endhint %}

**Who uses it:** QA engineers on billing or reporting features where a PDF is the deliverable

## Setting it up

{% stepper %}
{% step %}
Open Model → Application → PDF.
{% endstep %}
{% step %}
Set the file name, path, and type.
{% endstep %}
{% step %}
Add the text/image checks the document must satisfy.
{% endstep %}
{% step %}
Save for use in Design's verification steps.
{% endstep %}
{% endstepper %}

## Media

_Screenshot coming soon._

{% file src="../../assets/video/model-pdf.mp4" %}
Video walkthrough — placeholder file, real screen recording to be added
{% endfile %}

## Related

See the module [glossary](../glossary.md) and [edge cases](../edge-cases.md) for how PDF connects to the rest of Application Model.

