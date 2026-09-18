# Welcome to TerrA

TerrA is Tristha Global's enterprise test automation platform. It covers the
full lifecycle of a QA effort — modeling the systems under test, designing
test cases and scenarios, automating keywords and scripts, planning and
running execution, and tracking defects that come out of it.

This guide walks through each module in the order most teams touch them.

## Modules covered here

<table data-view="cards">
<thead><tr><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead>
<tbody>
<tr><td><strong>Model</strong> · in-depth guide</td><td>Where every system under test gets defined: web pages, mobile screens, APIs, PDFs, and billing records all become reusable objects here. Everything Design and Automation build later depends on what gets captured in Model first.</td><td><a href="model/README.md">model/README.md</a></td></tr>
<tr><td><strong>Design</strong> · in-depth guide</td><td>Turns Model's objects into actual tests. A Testcase is one executable check; a Scenario chains several together into a full journey, like checkout or onboarding.</td><td><a href="design/README.md">design/README.md</a></td></tr>
<tr><td><strong>Automation</strong> · in-depth guide</td><td>The shared toolbox behind every test step: Keywords, Scripts, Formulas, and Libraries that keep the same logic from being rebuilt case after case.</td><td><a href="automation/README.md">automation/README.md</a></td></tr>
<tr><td><strong>Hub</strong></td><td>Plans releases, iterations, and execution runs, mapping test coverage onto a real calendar.</td><td><a href="hub/README.md">hub/README.md</a></td></tr>
<tr><td><strong>Defect</strong></td><td>Tracks the bugs test execution surfaces, linked back to the test cases that found them.</td><td><a href="defect/README.md">defect/README.md</a></td></tr>
<tr><td><strong>MDM</strong></td><td>Manages the test data — payment scenarios, customer profiles, edge-case datasets — everything else in TerrA runs on.</td><td><a href="mdm/README.md">mdm/README.md</a></td></tr>
<tr><td><strong>TRAM</strong></td><td>Reserves and controls the physical and virtual devices mobile testing runs against.</td><td><a href="tram/README.md">tram/README.md</a></td></tr>
<tr><td><strong>Sipay</strong></td><td>Adds payment-gateway-specific testing support for flows that need a real payment step.</td><td><a href="sipay/README.md">sipay/README.md</a></td></tr>
</tbody>
</table>

Start with **Model** if you're setting up a new project, or jump straight to
**Design → Test Case** if the model is already in place and you just need to
build a test.
