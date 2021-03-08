---
title: 'Two Forms of Pre-rendering'
date: '2020-01-01'
---

Next.js has two forms of pre-rendering: **Static Generation** and **Server-side Rendering**. The difference is in **when** it generates the HTML for a page.

-**Static Generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is the _reused_ on each request.
-**Server-side Rendering** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** wich pre-rendering form to use for each page. YPu can create a "hybrid" Next.js app by using Static Geneartion for most pages and using Server-side Rendering for others.
