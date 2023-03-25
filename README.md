
# Awesome-AI-Coding

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
![Made With Love](https://img.shields.io/badge/Made%20With-Love-orange.svg)

A list of of AI coding topics.

## LLM Models

- [PolyCoder 160M/400M/2.7B](https://github.com/VHellendoorn/Code-LMs)
- [CodeGen 350M/2B/6B/16B](https://github.com/salesforce/CodeGen)
- [TransCoder](https://github.com/facebookresearch/CodeGen)
- [CodeGeeX 13B](https://github.com/THUDM/CodeGeeX)
- [SantaCoder 1.1B](https://huggingface.co/bigcode/santacoder)
- [InCoder 1B/6B](https://github.com/dpfried/incoder)

## Datasets

- [The Pile](https://huggingface.co/datasets/the_pile)
- [The Stack](https://huggingface.co/datasets/bigcode/the-stack)
- [CodeContests](https://github.com/deepmind/code_contests)

## Projects
- [BigCode Dataset](https://github.com/bigcode-project/bigcode-dataset): Data preprocessing to filter *The Stack*, used to created *SantaCoder*
- [Fauxpilot](https://github.com/fauxpilot/fauxpilot): Code completion server with *CodeGen*.
- [CodeGPT.nvim](https://github.com/dpayne/CodeGPT.nvim): ChatGPT in neovim.
- [org-ai](https://github.com/rksm/org-ai): Emacs org-mode with OpenAI APIs.

## Papers & Blogs
- [Competition-level code generation with AlphaCode](https://deepmind.com/blog/article/Competitive-programming-with-AlphaCode)
- [RepoCoder: Repository-Level Code Completion Through Iterative Retrieval and Generation](https://arxiv.org/abs/2303.12570)
  * Combined LLM completion and CodeSearch
  * CodeGen-350M + BoW based snippet search beat Codex
- [Repository-Level Prompt Generation for Large Language Models of Code](https://arxiv.org/abs/2206.12839)
  * Generate proposals candidates based with prios, e.g imports, files from same dirs.
  * Use a proposal candidate classifier to select based proposals for LLM.
- [ML-Enhanced Code Completion Improves Developer Productivity](https://ai.googleblog.com/2022/07/ml-enhanced-code-completion-improves.html)
  * 500M Encoder-Decoder based model, fine tuned on Google's monorepo.
  * 34% acceptance rate for multi-line code completion suggestions.
- [Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/abs/2303.12712)
  * Chapter 3 on coding scenario.
  * Chat UX.
