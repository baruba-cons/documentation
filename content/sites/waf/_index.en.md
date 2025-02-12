+++
title = "Web Application Firewall (WAF)"
menuTitle = "WAF"
weight = 60
layout = "man"
tags = ["http", "site", "waf"]
+++

A [WAF](https://en.wikipedia.org/wiki/Web_application_firewall) examines every HTTP request to protect the web applications from the various attack vehicles to minimize infections. It may allow them to transit to the application or block them, alert, record whether they are deemed malevolent.

{{< fig "waf.en.png" "Path of an HTTP request faced with a WAF">}}

- [Use WAF]({{< ref "sites/waf/use-waf" >}})

alwaysdata uses WAF ModSecurity and all of the [OWASP Modsecurity Core Rule Set](https://coreruleset.org/) (CRS).

---
Icons: The Noun Project
