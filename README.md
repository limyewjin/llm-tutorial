# YJ's Prompt Engineering List

A hand-picked collection of high-quality resources for learning prompt engineering with Large Language Models. Learn the techniques and principles for crafting effective prompts that unlock an LLM's full potential. This curated list focuses on practical resources without the noise.

---

## 🔍 Lessons from the Industry
Real-world insights from practitioners:
- [What We Learned from a Year of Building with LLMs (Part I)](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/)  
- [What We Learned from a Year of Building with LLMs (Part II)](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-ii/)  
- [What We Learned from a Year of Building with LLMs (Part III): Strategy](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-iii-strategy/)  
- [Lessons after a half-billion GPT tokens](https://kenkantzer.com/lessons-after-a-half-billion-gpt-tokens/)  
- [Reasoning (models) best practices](https://platform.openai.com/docs/guides/reasoning-best-practices) — OpenAI's guide to building with reasoning models (such as OpenAI o1 and o3-mini) as they are different from using  GPT models
- [AI prompt engineering: A deep dive (YouTube)](https://www.youtube.com/watch?v=T9aRN5JkmL8&ab_channel=Anthropic) by Anthropic — reflections on how prompt engineering has evolved, practical tips, and thoughts on how prompting might change as AI capabilities grow.

---

## 🕵️ AI Agents
- [Why Vertical LLM Agents Are The New $1 Billion SaaS Opportunities (YouTube)](https://www.youtube.com/watch?v=eBVi_sLaYsc&ab_channel=YCombinator) and in particular see [20:40 - Approaching prompt engineering step by step](https://www.youtube.com/watch?v=eBVi_sLaYsc&t=1240s)
- [Building effective agents](https://www.anthropic.com/research/building-effective-agents) from Anthropic — also see [Tips for building AI agents (YouTube)](https://www.youtube.com/watch?v=LP5OCa20Zpg&ab_channel=Anthropic)
  
---

## 📝 Papers
- [The Prompt Report: A Systematic Survey of Prompting Techniques (Schulhoff et al., 2024)](https://arxiv.org/abs/2402.07927) — A comprehensive taxonomy of 58 prompting techniques comparing their effectiveness in LLM-based applications.
- [Prompt Design and Engineering: Introduction and Advanced Methods (Amatriain, 2024)](https://arxiv.org/abs/2401.14423) — A structured overview of fundamental and advanced prompting techniques, including Chain-of-Thought, Reflection, and AI agent design.
- [Chain-of-Thought Prompting (Wei et al., 2022)](https://arxiv.org/abs/2201.11903) — A seminal paper that showed how giving a model a chain of thought, i.e. prompting it with step-by-step reasoning examples, dramatically improves performance on complex tasks

---

## 📖 "Official" Guides
Selected guides from major LLM providers:
- [Introduction to prompt design - Gemini API](https://ai.google.dev/gemini-api/docs/prompting-intro)  
- [Prompt engineering guide - OpenAI](https://platform.openai.com/docs/guides/prompt-engineering)  
- [Anthropic's Prompt Engineering Interactive Tutorial - Anthropic](https://github.com/anthropics/prompt-eng-interactive-tutorial)  
- [Cohere’s Guide to Crafting Effective Prompts](https://docs.cohere.com/docs/prompt-engineering)  

---

## 🎓 Tutorials & Guides
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/limyewjin/llm-tutorial/blob/main/Prompt_Engineering_Tutorial.ipynb) — YJ's Prompt Engineering Tutorial

- [Learn Prompting](https://learnprompting.org)  
- [ChatGPT Prompt Engineering for Developers (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)  
- [Prompt Engineering Guide (DAIR AI)](https://promptingguide.ai/)

---

## 🛠 More LLM Learning Resources
Additional high-quality **GitHub repositories** and **resources** for learning about LLMs, fine-tuning, and deployment:
- [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering) — hand-curated resources for Prompt Engineering. 
- [Awesome LLM Papers](https://github.com/Hannibal046/Awesome-LLM) — A collection of the most important papers on LLMs.  

---

## Short Note on Autotuned Prompting

Even in an article titled [AI Prompt Engineering Is Dead](https://spectrum.ieee.org/prompt-engineering-is-dead), there is a quote at the end:
> I think there are going to be prompt engineers for quite some time, and data scientists.
> It’s not just asking questions of the LLM and making sure that the answer looks good.
> But there’s a raft of things that prompt engineers really need to be able to do.

Autotuning prompts are based on optimization techniques, but they lack human intuition about intent, user experience, and real-world applicability. LLMs are often deployed in scenarios where nuance, tone, and user expectations play a critical role—things that a human-crafted prompt can better align with. Autotuning techniques can help automate certain aspects of prompt generation, but human expertise in designing, refining, and adapting prompts remains critical—especially for complex, dynamic, and user-facing applications.

---

## 🚀 Contributing
We prioritize quality over quantity. To contribute:
1. Ensure the resource offers unique insights not covered by existing entries
2. Include a one-line description of what makes it valuable
3. Submit a PR with your suggestion

---
  
Happy Prompting! 🚀
