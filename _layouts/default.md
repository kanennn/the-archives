---
layout: base
---
<main>
    {% include header.html title=page.title author=page.author
    domain=page.domain backlink=page.backlink %}
    <section class="content">{{content}}</section>
</main>