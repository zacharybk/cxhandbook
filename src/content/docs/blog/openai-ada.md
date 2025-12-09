---
title: "OpenAI & Ada Implementing ChatGPT"
date: 2022-12-22
author: "Zach Bouzan-Kaloustian"
description: "Key takeaways from Ada's webinar on bringing generative AI to customer service"
draft: false
tags: ["OpenAI", "ChatGPT", "AI"]
---

## The ChatGPT Opportunity: Bringing Generative AI to Customer Service

**Host & Speakers**
Mike Murchison, Co-Founder & CEO at Ada
Yaniv Murchison, Head of Support Engineering & Community at OpenAI
Yochai Konig, VP, Machine Learning & AI at Ada
![Image of speakers](https://github.com/zacharybk/cxhandbook/blob/master/static/images/adaceo.png?raw=true)

## Zach's key takeaways:
Here are my notes and thoughts form the discussion. You can watch and listen to the recording [here](https://get.ada.cx/chatgpt-webinar?hsCtaTracking=customerexperiencehandbook.com):
- AI is a multiplier. It reduces some tasks from days to minutes.
- Generative AI is actually great at the most complicated questions, not just the simple questions that deflection handles today.
- Read this blog post and the accompanying [links](https://www.ada.cx/posts/understanding-the-business-implications-of-chatgpt-and-large-language-models-llms)
- Yaniv's Team at OpenAI is actively using GPT-3 in their own support, which is pretty cool. He said that when then went from roughly zero to 5m users in a week, they couldn't have scaled without this
- Generative AI - It says it in the name, but I had a revelation that it is actually generating new content that didn't exist before. This is the power that you see when you use Open AI's chat
    -GPT-3 is a form of [generative AI](https://chat.openai.com/)
- For it to be implemented well, take action, and know what to say, there are a lot of challenges at companies
    - You need your processes well documented. Think about it in terms of being able to code the answer.
    - You need integrations into your systems via APIs
    - "Data layer need to be up-to-date, which is a huge challenge" - Yaniv
- Buy vs Build is a huge decision
    - It's like buying or building Zendesk
- This AI is really good and helpful at a few things
    - Semantic understanding and clustering of information. Will help you move away from keyword tagging
    - Create new content for you
    - It is also very good at confidently being wrong (not on purpose of course)
    - Retrieving an answer and document, and then generating new content. Move from prescriptive answer to generative answer.
- Async channels like Email allow for a lot of human validation before sending an answer
    - Here's a great demo of that in Gorgias with Yuma.ai - https://yuma.ai/ai-ticket-assistant
- Live channels like chat, SMS, maybe even phone - Need to overcome the risk of AI taking "incorrect" actions. Providing answers in real time reduces your ability to validate, so you really need your processes well-established
    - Zach's take is that you would want to triage first, and once you build confidence in the tool over time, then take action
- AI is good at knowing how to answer a question, but it won't always know the root cause, which is what you need to push for. If you leverage its ability to cluster information and then analyze it, you'll be further. Here's an example from OpenAI
    - OpenAI is not accessible in all countries, and the website should say that to the user
    - Some users in blocked countries still get thorough, and sign up
    - When you sign up you must validate with a phone number, and the system should kick you out if you're in a blocked country
    - If a user doesn't see that information on the website, and asks ChatGPT what's wrong, ChatGPT will tell them how to authenticate, but might not know why they're unable.
    - The real problem is a missing notice on the site
