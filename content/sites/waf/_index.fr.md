+++
url = "/fr/sites/waf/"
title = "Pare-feu applicatif web (WAF)"
menuTitle = "WAF"
weight = 60
layout = "man"
tags = ["http", "site", "waf"]
+++

Un [WAF](https://fr.wikipedia.org/wiki/Web_application_firewall) exa­mine chaque requête HTTP pour protéger les applications web face à différents vecteurs d'attaques pour minimiser les infections. Il peut les auto­ri­ser à tran­si­ter jus­qu’à l’ap­pli­ca­tion, ou les blo­quer, aler­ter, consi­gner si elles sont jugées mal­veillantes.

{{< fig "waf.fr.png" "Parcours d’une requête HTTP face à un WAF" >}}

- [Utiliser le WAF]({{< ref "sites/waf/use-waf" >}})

alwaysdata utilise le WAF ModSecurity et l'ensemble de règles libres [OWASP Modsecurity Core Rule Set](https://coreruleset.org/) (CRS).

---
Icônes : The Noun Project
