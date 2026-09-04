---
title: Two years in IT
date: 2026-09-04 19:46:00 +1200
categories: [hobbies]
tags: [coding]
---

In November 2022, the first version of ChatGPT was released. AI started to penetrate everyday life.

One year later, I enrolled in a master’s programme in computer science. In the meantime, AI rapidly grew and evolved.

Another half year later, I luckily got an internship at a software company, where *AI first* later became one of the company’s main policies.

And recently, after staying with the company for more than two years, my position was unluckily disestablished. Meanwhile, AI continues to thrive.

Looking back, it was probably not an ideal time to jump to the IT industry as a newcomer when AI was emerging. To borrow a metaphor teasingly used by some people, it was almost like joining the Kuomintang in 1949, which would soon retreat to Taiwan while the Chinese Communist Party became the governing authority on the mainland China.

(*Disclaimer: I am not interested in politics ; )*

But it is what it is.

Although the IT industry has been brutally changed since the arrival of generative AI, a senior I admire a lot once said: “We need to make sure the road to seniors still exists.” And for me, at least the past two years have helped me know what makes a good senior, as I have seen some of them so far.

No one can deny how powerful AI already is, and who would be foolish enough to want to compete with AI, which is armed with the full spectrum of knowledge accumulated by human society. In some ways, AI is an interface that connects us to the grand storage room of human civilisation, without requiring us to understand all the low-level implementation details, so-called abstraction.

“Ask anything.” says ChatGPT.  Philosophy, mathematics, physics, biology, recipes, nutrition, culture and relationships, literally anything. Just be mindful that “I can make mistakes and provide incorrect information. ~~Just like a human.~~”

AI companies are trying to find anything nutritious they can find on earth to feed AI, and second-hand bookstores in many corners of the world including several in New Zealand, have reportedly received large numbers of anonymous orders from some specific warehouses in America. Just a bit unusual to go unnoticed.

Everyone can now create something with the help of AI: images, music, songs, videos, stories, comics and apps. These creations are not necessarily entirely original, but surely something that can be shared with others. A few months ago, on the same day, three friends sent me apps they had made with *Lovable* and asked for feedback. One was quite simple, and that friend emphasised that she had spent only five minutes making it. Another was quite impressive and feature-rich from a UI perspective, almost like those in the App Store.

I also did some vibe coding myself to build some small web apps. It was surely satisfying to get something functional and visually appealing back within minutes or hours. However, I had to make many compromises when accepting AI’s work, especially its UI decisions. But even a single colour can have infinite shades, how can I expect AI to interpret my intentions perfectly, not to mention the inherently ambiguous nature of natural language.

Image generation works in similar ways: I provide a prompt, AI creates something that satisfies the basic requirements, and then I refine the prompt repeatedly to let the result closer to what I have in mind. Since I cannot draw, I am unable to sketch my ideas and control every detail by hand, and because much of AI-assisted creation is essentially about modifying and rearranging existing patterns, the final output is usually again, a compromised one.

When building new apps, the developers never need to worry about historical contexts, therefore can focus on instructing the AI to use any fancy new technologies they prefer to implement own thoughts. However, working with any production level application is different - developers must work within various constraints of the existing architecture, codebase, and tech stack, a little like dancing in chains, not always have room for freestyle or compromises. Production systems also have more concerns around security, performance and maintainability, so a broad understanding of the underlying infrastructure and system internals is truly beneficial. In fact, there's a growing view that the advent of agentic engineering has shifted the value of developers away from simple code generation and toward problem-solving, system design, and architecture, which poses new, higher expectations for developers. This echoes what that senior said: "we need to make sure the road to seniors still exists."

Back in November 2023, the first program I wrote was a services and parts management system for a car repair shop, in Python. It was a simple student exercise in an isolated environment - it ran in the terminal, followed instructions, and handled the user cases I had considered. At the time, I didn't have a clear mental picture of how a program actually works end to end. Concepts like compiling, concurrency, the differences between statically and dynamically typed languages, and operational concerns such as version control, compatibility and security were all beyond my comprehension.

Later, when I started working on enterprise-scale projects, I finally began to develop a practical understanding of how software runs in the real world. In particular, I came to realise that writing one's own code and reading others' code, even when written in the same programing language, can require quite different levels of difficulty. That's when I started to appreciate why coding is a social activity, and why the author of *Clean Code* placed such emphasis on things like meaningful naming and the avoidance of unnecessary comments, especially commented-out code.

Now with AI, many developers I know spend more time reviewing AI-generated code rather than writing code from scratch. Compared to AI’s ability to generate code, code review is apparently an area where a lot of AI noise can be found, partly because AI-generated code itself can contain bugs and security issues, and partly because AI’s ability to review code reliably is still limited. So developers are becoming more like guardians of code, making sure only clean and safe code is released to production environment (in an ideally perfect world, of course), which might actually be a fun, though higher-requirement, higher-responsibility, part of the developer's job.

Some AI companies have started experimenting with outcome-based pricing, where customers [only pay when the AI actually gets the job done](https://the-decoder.com/openai-starts-charging-some-customers-only-when-its-ai-actually-works/), instead of paying for usage or a subscription. It's probably unlikely, though, that one day AI companies will say they're happy to be responsible for losses caused by use of AI-generated code, more likely, something similar to AWS's *Shared Responsibility Model* will emerge.

Last month, the Rust community added the [LLM usage policy](https://forge.rust-lang.org/policies/llm-usage.html#summary) to its official repository and something is quite interesting in there hence i quote it here:

> It’s fine to use LLMs to answer questions, analyse, distill, refine, check, suggest, and review. But not to **create**.

> LLMs work best when used as a tool to write *better*, not *faster*.

The policy also specifies some *allowed*, *banned*, and *allowed with caveats* uses. For example, *"LLMs can be used when you are the only person who sees the output e.g. asking an LLM questions about an existing codebase, asking an LLM to summarize comments on an issue or PR, asking an LLM to privately review your code or prose."* And below behaviours are prohibited: *"replacing human judgment with LLM judgment, requiring contributors to use an LLM, posting comments originally generated by an LLM from a personal account, submitting documentation originally created by an LLM, and treating an LLM review as sufficient reason to merge or reject a change"*, etc.

**TL;DR:** It is interesting to see where AI takes us, not just in the world of coding. While it might not be an ideal time to be a junior developer in the age of AI, as a technology optimist who does find coding fun in many ways, I still feel lucky to have come across some good developers so far, and I will surely, gradually, level up in the areas I put my time and care into.
