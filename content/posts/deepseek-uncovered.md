---
title: "DeepSeek Uncovered"
date: 2025-12-09
tags: ["events", "ai", "deepseek", "open-source"]
summary: "A Tech & Meet session with Dimitri Casier on DeepSeek, the open-source AI challenger from China."
cover:
  image: "/images/deepseek-compute.png"
  alt: "Global AI compute comparison slide"
---

![Global AI compute comparison slide](/images/deepseek-compute.png)

DeepSeek had been everywhere in the news for a few weeks before this session. I had a rough sense of what it was — an open-source AI model from China that somehow matched GPT-4 performance and apparently rattled investors enough to wipe billions off Nvidia's market cap in a single day. That's a headline, not an explanation. Dimitri Casier actually explained it.

![DeepSeek R1 vs OpenAI slide](/images/deepseek-r1.png)

The compute comparison landed first. DeepSeek V3 was trained on around 2,000 GPUs. Meta trained Llama 4 on 100,000. Same category of model, fifty times less hardware. The slide was right there and I still read it twice. The claim is that R1 costs about 96% less to run than OpenAI's O1. You can argue about methodology and what exactly is being compared, but even discounted heavily those numbers are hard to shrug off. The assumption for a long time has been that better AI just means more chips. DeepSeek is a pretty direct challenge to that.

![Dimitri presenting the chip count comparison](/images/deepseek-chips.png)

The architectural stuff was harder to follow. The part about compressing long context into something resembling internal image representations went by quickly, and I didn't fully get it. I understood enough to see why it's interesting — it's a different approach to scaling context length without just throwing more compute at the problem — but I'd need to sit with it longer to actually explain it to someone else.

What I keep coming back to is the open-source angle. There's a slide showing China's total AI chip count versus the US, and the gap is enormous. DeepSeek built a competitive model anyway, partly through smarter architecture choices, partly by being fully open. The closed labs have more hardware and more money. The open-source community has more people reading the code, finding problems, and building on top of it. It's not obvious which advantage compounds faster.

![Live terminal demo showing DeepSeek reasoning through a logic puzzle](/images/deepseek-demo.png)

Dimitri did a live demo in the terminal — DeepSeek working through a logic puzzle step by step, showing its reasoning out loud before giving a final answer. It's a small thing but it made the concept of chain-of-thought reasoning click in a way that a slide describing it doesn't. Watching the model second-guess itself mid-answer and correct course is genuinely strange to see.

The broader takeaway from the session is that the AI landscape in 2025 looks different from what it did two years ago. The gap between open and closed models is closing faster than most people predicted, and the assumption that cutting-edge AI is a US-only story is clearly wrong.
