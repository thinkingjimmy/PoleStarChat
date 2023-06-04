# PoleStar Chat

中文版本：

## 🤔 Why

Many people have similar views on AI to [JARVIS](https://en.wikipedia.org/wiki/J.A.R.V.I.S.), the personal assistant invented by Iron Man. They hope that AI can be a "personal super intelligent assistant" that can replace humans to do many things. 

However, I don't want future AI to be like JARVIS because it feels like a privilege for the rich and is both aloof and distant. Instead, I hope future AI can be like [Doraemon](https://en.wikipedia.org/wiki/Doraemon). It should be approachable, even for middle-class families like [Nobita Nobi](https://en.wikipedia.org/wiki/Nobita_Nobi), and integrate into your life, work, and learning like a presence that is like a family member, friend, or teacher, not a tool with a high and cold personality. Lastly, unlike so-called intelligent assistants that "replace" humans, it should try its best to "provide" tools/methods and help humans. 

In summary, "an assistant that enhances human intelligence" would match the ideal image of AI in my mind.

However, ideals are abundant, and reality is bony. 

Since the release of ChatGPT, I have been using it. However, in the process of using it, I found that although its abilities are powerful, you will face many difficulties if you want to unleash its full potential:

- Firstly, to improve the accuracy of AI's responses, you need to learn many skills. I spent over ten hours learning about Prompt Engineering and even wrote a nearly 100,000-word tutorial on Prompt Engineering for this purpose. After using prompt skills, the accuracy of AI's responses did indeed improve significantly.
- However, I encountered the second problem, which is that inputting prompt information is very troublesome. It requires frequent copying and pasting, which is highly inefficient.
- Lastly, payment problems may arise, just like with my experience. Payment can be difficult and easy to be banned. Not to mention, the subscription fees each month are still too expensive for many people.

Since the product is not satisfactory, I tried to find a good solution on the market. Unfortunately, I tried various tools, and many of them were great, but none of them met all my needs. Therefore, we decided to develop our own.

## 😎 Differences

The development of AI is still in its early stages, and many technologies are not yet refined. There is still a long way to go to achieve our goals. However, this does not mean that we cannot take the first step towards making AI more approachable:

1. Improve the efficiency of using prompts:
    1. You can call up pre-made prompts using familiar interaction operations and customize prompt parameters according to their needs.
    2. In the future, we hope to reduce the difficulty of writing prompts.
2. Lower the threshold for model invocation:
    1. Our application allows you to simultaneously use multiple models, such as GPT-3 and Stable Diffusion.
    2. We support a pay-as-you-go payment model, where you pay for the number of tokens you use, thus reducing usage costs.
3. Improve AI's response accuracy:
Another obstacle for using AI is that it may generate nonsensical responses in some areas. To solve this problem, we will support the ability to customize databases in the future. This way, AI can answer based on the contents of a knowledge base, improving the accuracy of its responses.
4. Broaden the scope of application:
To better integrate AI into your life, work, and learning, we will support the ability to call external APIs in the future. For example, you could use text input to let AI help you book an appointment on Google Calendar.

## 🚀 Features

You can check the development progress of the following features through [PoleStar Chat - Public Roadmap](https://www.notion.so/PoleStar-Chat-Public-Roadmap-d4d9a483564f409ba16ff22792c806f9?pvs=21) , and we welcome feedback in our [Discord server](https://discord.gg/esyCEGhmq9).

**IM App Design:**
To make the product more approachable, the product's design adopts IM interaction. You can create a chat room (Channel) and talk directly to the AI assistant through the input box like using other IM products. Also, to solve the problem of difficulty in calling prompt templates, you can quickly call prompts through the AT method, like this:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/29aaa9d3-7f16-4f9d-a396-510ef6113081/Untitled.png)

**Support for multiple models:**
Currently available tools have two main issues: difficulty in calling prompts and support for only single models or LLM models. To lower the threshold for model usage, we will support the use of multiple models in the future, such as text-to-image models or open-source models in vertical fields. In the next version, you will be able to use AT Text2Image Bot in the IM to generate images from text using AI.

**Pay-as-you-go mode:**
The last and perhaps most significant obstacle for users is the price. OpenAI membership costs $20 per month, Midjourney costs $30 per month, but for individual use, it may not be feasible to use them at full capacity, and the $50 monthly fee is still expensive for many people. To solve this problem, we will support paying for Tokens and pay-as-you-go model calls in the future. Simply put, you pay for what you use, reducing usage costs.

**Support for custom data sources:**
In addition to supporting multiple models, we also plan to support custom data sources. This means that in the future, you can use our tool to build your own knowledge base AI Bot.

**Open-source code:**
As the saying goes, many hands make light work. We know that individual efforts are not enough to get more people to use AI, so we decided to introduce the power of the open-source community. We expect to open-source our code (excluding server-side code) around July, and everyone can use our product for secondary development.
