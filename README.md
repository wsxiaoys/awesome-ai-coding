
# Awesome-AI-Coding

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-orange.svg)](https://github.com/wsxiaoys/awesome-ai-coding)

A list of of AI coding topics.

[Open a pull request](https://github.com/wsxiaoys/awesome-ai-coding/pulls) to add or edit this list. 

## Projects

- [BigCode](https://github.com/bigcode-project): open scientific collaboration run by Hugging Face.
- [Fauxpilot](https://github.com/fauxpilot/fauxpilot): Code completion server with *CodeGen*.
- [CodeGPT.nvim](https://github.com/dpayne/CodeGPT.nvim): ChatGPT in neovim.
- [org-ai](https://github.com/rksm/org-ai): Emacs org-mode with OpenAI APIs.
- [CodeAlpaca](https://github.com/sahil280114/codealpaca): LLaMA trained on code instruction following.
- [Autodoc](https://github.com/context-labs/autodoc): Generate codebase documentation use LLM (OpenAI / Alpaca)

## Datasets

- [The Pile](https://huggingface.co/datasets/the_pile)
- [The Stack](https://huggingface.co/datasets/bigcode/the-stack)
- [CodeContests](https://github.com/deepmind/code_contests)
- [CodeSearchNet](https://github.com/github/CodeSearchNet)

## LLM Models

- [PolyCoder 160M/400M/2.7B](https://github.com/VHellendoorn/Code-LMs)
- [CodeGen 350M/2B/6B/16B](https://github.com/salesforce/CodeGen)
- [TransCoder](https://github.com/facebookresearch/CodeGen)
- [CodeGeeX 13B](https://github.com/THUDM/CodeGeeX)
- [SantaCoder 1.1B](https://huggingface.co/bigcode/santacoder)
- [InCoder 1B/6B](https://github.com/dpfried/incoder)

## Embedding Models
- [CodeBERTa](https://huggingface.co/huggingface/CodeBERTa-small-v1)

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
- [Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/abs/2303.12712): Chapter 3 on coding scenario. Chat UX.
- [Efficient Training of Language Models to Fill in the Middle](https://arxiv.org/abs/2207.14255): Train decoder-only model with special <FIM> token with suffix context.
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761): LLM as API glue layer.

## Products & Startups

- [Copilot](https://github.com/features/copilot) + [Copilot X](https://github.com/features/preview/copilot-x)
- [Codeium](https://www.codeium.com/)
- [CodeComplete.AI](https://codecomplete.ai/)
- [Codify](https://codify.smallcloud.ai/)
- [Cody](https://docs.sourcegraph.com/cody)
- [Amazon Codewhisperer](https://aws.amazon.com/cn/codewhisperer/)
- [Replit Ghostwrite](https://replit.com/site/ghostwriter)
- [Tabnine](https://www.tabnine.com/)
- [AiXCoder](https://www.aixcoder.com/en/)
- [Turin Tech](https://www.turintech.ai/)
- [Cursor](https://www.cursor.so/)
- [Buildt](https://www.buildt.ai/)
- [Safurai](https://www.safurai.com/)
- [phind](https://www.phind.com/)
- [AskCodi](https://www.askcodi.com/)
