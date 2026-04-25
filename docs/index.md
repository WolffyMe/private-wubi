---
icon: material/card-search
title: "五笔全码拆解查询"
hide:
  - navigation
  - toc
  - footer
search:
  exclude: true
---

<link rel="stylesheet" type="text/css" href="static/css/styles2.css" />
<!-- <script src="https://cdn.jsdmirror.com/npm/hanzi-writer@3.7.2/dist/hanzi-writer.min.js"></script> -->
<!-- <script src="https://cdn.jsdelivr.net/npm/hanzi-writer@3.7.2/dist/hanzi-writer.min.js"></script> -->
<script src="static/js/lib/hanzi-writer.min.js"></script>

<main>
  <section>
    <form id="search-form" class="search-container">
      <input type="text" id="query-text" placeholder="请输入汉字..." />
      <button type="submit" id="query-button">🔍️</button>
    </form>
  </section>

  <section id="note-area">
    <p id="note-warning" class="note"></p>
  </section>

  <section>
    <table id="data-table">
    <thead></thead>
    <tbody></tbody>
    </table>
  </section>
</main>

<script type="module" src="static/js/index.js"></script>
