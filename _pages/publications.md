---
permalink: /publications/
title: \"Publications\"
author_profile: true
---

## Publications

{{ for publication in site.publications }}
- {{ publication.title }} ({{ publication.date }}) {{ publication.first_author }}
{{ endfor }}
