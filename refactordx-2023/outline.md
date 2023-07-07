# LLMs are not the product: integrations beyond chatbots

## Abstract

LLMs are the new hotness in product engineering, with chat experiences being the most prominent use-case. That's cool and all, but how can we use LLMs to enhance the workflows that our users are already familiar with? In this talk, we'll look at integration with LLMs - treating it not like a magical blackbox, but more like a service we integrate with to power more targeted features.

## Bio

Jason is a Staff Software Engineer at GitHub, currently working on future-facing Copilot-y things. He is best known for triaging peoples' bugs and feature requests, and for having a cat that sleeps on his toaster. 🐱🍞

---

# Outline

* Has anyone talked about AI yet today?
* So yes, it's a hot topic. What does it look like to use an LLM?
* Who am I
  * Copilot platform at GitHub
  * I work on "the glue" for integrating with LLMs at GitHub
  * I'm a software engineer, not a data scientist or machine learning person
  * I joined the Copilot organization with some hesitancy about AI. What convinced me of my role in it all was the idea of _integrating_ with LLMs, rather than just using them as a black box.
  * From coworker: "We should treat LLMs as a tool we use to build features, like a database or a cache."
* Looking broadly at how LLMs are being used - in particular, _generative_ models like GPT-3.5 and GPT-4.
* Most common use case is chat bots
* Chat experiences are limiting in how vague they are
  * Reference https://wattenberger.com/thoughts/boo-chatbots
* What's really interesting is applying LLMs selectively, to existing workflows
* Look at GitHub Copilot
* Look at Copilot X
* Doubling back: not all chat bots are _bad_. They just need some guidance.
* What Amelia talks about in her blog post are not unsolvable obstacles - they're just things that need to be solved.