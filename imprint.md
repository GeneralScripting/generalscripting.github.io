---
layout: page
title: Imprint
background: grey
---

{% if site.locale and site.locale != "" and site.locale != nil %}
<div class="col-lg-12 text-center">
	<h2 class="section-heading text-uppercase">{{ site.data.sitetext[site.locale].imprint.title | default: "Imprint" }}</h2>
</div>

General Scripting GmbH  
Brandenburgische Str. 24  
12167 Berlin  
{{ site.data.sitetext[site.locale].imprint.country | default: "Germany" }}
 
{{ site.data.sitetext[site.locale].imprint.vatid | default: "VAT-ID" }}:
DE278687284

{{ site.data.sitetext[site.locale].imprint.managing_director | default: "Managing director" }}:
Jan Schwenzien  
{{ site.data.sitetext[site.locale].imprint.registered | default: "Registered at" }}: AG Berlin-Charlottenburg, HRB 136317 B

**{{ site.data.sitetext[site.locale].imprint.contact | default: "Contact" }}**

{{ site.data.sitetext[site.locale].imprint.phone | default: "Phone" }}: +49 (0)171 5395196  
{{ site.data.sitetext[site.locale].imprint.email | default: "Email" }}: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
{% else %}
<div class="col-lg-12 text-center">
	<h2 class="section-heading text-uppercase">{{ site.data.sitetext.imprint.title | default: "Imprint" }}</h2>
</div>

General Scripting GmbH  
Brandenburgische Str. 24  
12167 Berlin  
{{ site.data.sitetext.imprint.country | default: "Germany" }}

{{ site.data.sitetext.imprint.vatid | default: "VAT-ID" }}:
DE278687284

{{ site.data.sitetext.imprint.managing_director | default: "Managing director" }}:
Jan Schwenzien  
{{ site.data.sitetext.imprint.registered | default: "Registered at" }}: AG Berlin-Charlottenburg, HRB 136317 B

**{{ site.data.sitetext.imprint.contact | default: "Contact" }}**

{{ site.data.sitetext.imprint.phone | default: "Phone" }}: +49 (0)171 5395196  
{{ site.data.sitetext.imprint.email | default: "Email" }}: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
{% endif %}
