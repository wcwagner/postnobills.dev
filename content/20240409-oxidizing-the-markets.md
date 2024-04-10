+++
title = "Oxidizing the markets"
date = 2024-04-09
[taxonomies]
tags = ["finance", "rust", "personal"]
+++

For years, I've been fascinated by software designed for financial markets. In my pursuit of knowledge, I've spent countless hours searching for insightful posts on [lobste.rs](https://lobste.rs/) and [HN](https://hckrnews.com/). I often found myself writing "posts" hidden away in my [Obsidian](https://obsidian.md/) vault to better understand what I read.[^1] These posts were useful not only for their content but also for the places they _led_ me to, such as [Matklad](https://matklad.github.io/2021/05/31/how-to-test.html#Links) referencing [tedinski](https://www.tedinski.com/2019/03/19/testing-at-the-boundaries.html). Over time, it felt increasingly important to _try_ and give back to the [small web](https://blog.kagi.com/small-web) of blogs that helped me so much.

To reciprocate, I have a two-part plan: first, to promote (i.e., [backlink](https://en.wikipedia.org/wiki/Backlink)) the authors and posts that have helped me; second, to create my own content that can help others. The latter is more focused, as my value is largely determined by my knowledge and experience. Two realities have emerged from my journey:

1. Rust's dominance in both quality and quantity of content
2. The lack of programming-related content in finance

I like Rust. I like finance. This post's title, **Oxidizing the Markets**, reflects both: the [oxidation](https://wiki.mozilla.org/Oxidation) (i.e., [rewrite it in Rust](https://github.com/fish-shell/fish-shell/pull/9512)) of software powering financial markets. While an exaggeration, I believe there are interesting problems to be solved, and this blog will document my learning process. I'm inspired by Jane Street's work in this space, creating [podcasts](https://signalsandthreads.com/), [blog posts](https://blog.janestreet.com/what-the-interns-have-wrought-2023/), [tech talks](https://www.janestreet.com/tech-talks/index.html), and [libraries](https://opensource.janestreet.com/incremental/) that take ["OCaml all the way down"](https://www.janestreet.com/tech-talks/ocaml-all-the-way-down/).

I plan to start by implementing a [FIX](https://www.fixtrading.org/online-specification/) (Financial Information eXchange) server, omnipresent in the indsutry, from basic foundations. I'll explain various _business_ concepts like [symbology](https://www.openfigi.com/about/symbology), [market structure](https://www.sifma.org/explore-issues/equity-market-structure/), [asset classes](https://en.wikipedia.org/wiki/ISO_10962), and [ECNs](https://en.wikipedia.org/wiki/Electronic_communication_network). These will provide real-world context for exploring technical approaches like [parser combinators](https://en.wikipedia.org/wiki/Parser_combinator), [incremental computation](https://en.wikipedia.org/wiki/Incremental_computing), [domain types](https://mmapped.blog/posts/25-domain-types.html#domain-type-classes), and [backpressure](https://en.wikipedia.org/wiki/Back_pressure).

[^1]: "What I cannot create, I do not understand." - [Richard Feynman](https://www.goodreads.com/quotes/8414-what-i-cannot-create-i-do-not-understand)
