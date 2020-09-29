---
layout: default
title: Události budoucí
keywords: nadcházející události
---
<div class="row">
  <div class="columns">
    <div class="o-section">
      <div class="o-section-inner">
          <header class="c-page-header">
            <h1 itemprop="headline" class="c-page-title">Aktuality</h1>
          </header>
          {% assign posts = paginator.posts %}
          {% include articles/list-responsive.html posts=posts %}
          {% include articles/pagination.html paginator=paginator %}
      </div>
    </div>
  </div>
</div>