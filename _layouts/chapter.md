---
layout: base
---

<main>
    {% include chapter-header.html title=page.title author=page.author
    domain=page.domain backlink=page.backlink chapter-number=page.chapter %}
    <section class="content"><section class="chapter">{{ content }}</section></section>
</main>
