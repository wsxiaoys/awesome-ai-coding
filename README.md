
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
- [Autodoc](https://github.com/context-labs/autodoc): Generate codebase documentation use LLM (OpenAI / Alpaca)
- [CodeAlpaca](https://github.com/sahil280114/codealpaca): LLaMA trained on code instruction following.
- [🐾 Tabby](https://github.com/TabbyML/tabby): An opensource / on-prem alternative to GitHub Copilot. 
- [e2b](https://github.com/e2b-dev/e2b): Opensource IDE powered by AI agents.
- [promptr](https://github.com/ferrislucas/promptr): CLI tool to operating on your codebase using GPT.
- [ChatIDE](https://github.com/yagil/ChatIDE): Extension let you talk to ChatGPT inside VSCode.
- [PromptMate](https://github.com/MateusZitelli/PromptMate): VSCode extension embed ChatGPT.
- [TurboPilot](https://github.com/ravenscroftj/turbopilot): CPU based copilot clone
- [CodeCapybara](https://github.com/FSoft-AI4Code/CodeCapybara): Open Source LLaMA Model that Follow Instruction-Tuning for Code Generation.
- [CodeTF](https://github.com/salesforce/CodeTF): A One-stop Transformer Library for State-of-the-art Code LLM
- [Rift](https://github.com/morph-labs/rift): A opensource LSP leveraging edge language model.

## Datasets

- [The Pile](https://huggingface.co/datasets/the_pile)
- [The Stack](https://huggingface.co/datasets/bigcode/the-stack)
- [CodeContests](https://github.com/deepmind/code_contests)
- [CodeSearchNet](https://github.com/github/CodeSearchNet)
- [The Vault](https://github.com/FSoft-AI4Code/TheVault)

## LLM Models

- [PolyCoder 160M/400M/2.7B](https://github.com/VHellendoorn/Code-LMs)
- [CodeGen 350M/2B/6B/16B](https://github.com/salesforce/CodeGen)
- [TransCoder](https://github.com/facebookresearch/CodeGen)
- [CodeGeeX 13B](https://github.com/THUDM/CodeGeeX)
- [SantaCoder 1.1B](https://huggingface.co/bigcode/santacoder)
- [InCoder 1B/6B](https://github.com/dpfried/incoder)
- [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b)
- [StarCoder 15B](https://huggingface.co/bigcode/starcoder)
- [CodeGen2](https://github.com/salesforce/CodeGen2)
- [CodeT5 / CodeT5+](https://github.com/salesforce/CodeT5)

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
- [Efficient Training of Language Models to Fill in the Middle](https://arxiv.org/abs/2207.14255): Train decoder-only model with suffix context using a special <FIM> token.
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761): LLM as API glue layer.
- [CodeCompose: A Large-Scale Industrial Deployment of
AI-assisted Code Authoring](https://arxiv.org/abs/2305.12050)
  * deployed as single line code completion to reduce latency to 300ms - 500ms.
  * 1.3B parameter size.
  * fine-tuning improves accuracy / bleu by 50% - 100%.
 
 
## Products & Startups

- [Copilot](https://github.com/features/copilot) + [Copilot X](https://github.com/features/preview/copilot-x)
- [Codeium](https://www.codeium.com/)
- [CodeComplete.AI](https://codecomplete.ai/)
- <s>[Codify](https://codify.smallcloud.ai/)</s> [refact.ai](https://refact.ai/)
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
- [MutableAI](https://mutable.ai/)
- [Machinet](https://machinet.net/) 
- [BlackBox](https://www.useblackbox.io/)
- [MetaBob](https://www.metabob.com)
- [ZZZ Code AI](https://zzzcode.ai/)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=wsxiaoys/awesome-ai-coding&type=Date)](https://star-history.com/#wsxiaoys/awesome-ai-coding&Date)
