---
title: "Rust: thoughs after 1 month"
layout: single
permalink: /posts/rust1
date: 2021-11-16
tags: [posts]
header:
    teaser: "/assets/for_posts/rust/rust.png"
---

<figure>
  <img src="/assets/for_posts/rust/rust.png" alt="this is a placeholder image">
</figure>

## Background

I have always wanted to learn a low level and learn it well to get into the world of performance demanding applications like computer graphics, algorithm implementation, etc. The obvious choice was always C++ due to its rich history and legacy libraries. I started and restarted learnig C++ couple of times due to different reasons, but never got the the level where i can call myself a C++ developer. Writting a medium size project or anything beyond a few hundred lines of code in C++ has often been followed by constant anxiety since it is perfectly valid to write and compile a code that will leak memory or produce a segmentation fault. Writting correct C++ felt like an unreachable goal acheivable by years of practice.
{: style="text-align: justify;"}

Of course when i first heard all the hype about _the C++ competitior_ Rust with a slogan _"fast, reliable, productive: pick three."_ I got interested. Taking more time to read about its features like modern compiler that that ensures memory and thread safety i took a decision to try it. Here a few videos that reinforced my will to give Rust a chance:
{: style="text-align: justify;"}

- [Rust at Mozilla](https://www.youtube.com/watch?v=8EPsnf_ZYU0)

- [What can you build in Rust?](https://www.youtube.com/watch?v=MraEYwI9C5o)

## What i did last month to get started
- Completed basic part of [the Rust book](https://doc.rust-lang.org/stable/book) up to chapter 12 to cover the basics.
- Practiced solving challenges using Rust on [Exercism](https://exercism.org/tracks/rust).
- Read a book [Rust in Action: Systems programming concepts and techniques](https://www.manning.com/books/rust-in-action) by Tim McNacamara
{: style="text-align: justify;"}

## What i like about Rust?
From the top of my head, those are the few points that blew me away:
- `cargo` is what C++ was missing for me all along. `pip` or `dotnet` users will feel at home since it is both a package manager, and a build tool. Starting a fresh project with `cargo` is literally effortless, compared to building a C++ projects.
- Strict compiler. This is a questionable feature for some people, however, writting C++ as a unexperienced developer can sometimes feel like walking over a minefield of segmentation faults. Rust is a very safe language, and the compiler is your best friend and teacher. Rust compiler is built in way that wont let you create memory unsafe / thread unsafe code unless you explicitly ask it to let you do this with the `unsafe` block (similar to C#). I think this is a good feature for those of us that just start working with system level language.
- Very good error messages. Lets be honest, often times C++ error messages are big but make little sense. Rust errors are very descriptive and guide you to find the fix much more effectively.
- Community. The comunity is what Rust creators themself put first. Low level systems programming has a somewhat legendary reputation of being accessible to a small amout of smart people that spent a excessive amount of time practicing it. The first thing you see vising [Rust website](https://www.rust-lang.org/) is: _A language empowering everyone
to build reliable and efficient software_. Buildig a large friendly community for systems programming is Rusts priority number one, and from my experience based on the documentation, question forums and other media it is true.
- `snake_case` is the defacto standart formatting.
{: style="text-align: justify;"}

## What i dont like about Rust?
Short answer is, nothing, but i will try my best to update this section for the next blog about my Rust experience.
{: style="text-align: justify;"}

## What's coming next?

A blogpost about half a year progress where i will implement some CLI's or rewrite some of my older code in Rust.
{: style="text-align: justify;"}

