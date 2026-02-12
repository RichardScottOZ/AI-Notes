# AI-Notes
Useful references in this area

## Search
- Perplexity - https://www.perplexity.ai/    - Given google's descent into mediocrity
- Duck AI - https://duckduckgo.com/?q=DuckDuckGo+AI+Chat&ia=chat&duckai=1
- Scira - https://scira.ai/

## Robots
- ChatBot Arena - https://lmarena.ai/    - ManyBots?
- ChatGPT - https://openai.com/index/chatgpt/
- Claude - https://claude.ai/login?returnTo=%2F%3F    - You have to try Mr Shannon at least once, right?
- Deepseek - https://chat.deepseek.com/    - Anyone not like 10x cheaper?
- Gemini - https://gemini.google.com/app/bf9ff53a9cd3ff1e?hl=en-AU    - Just like the old ad
  - https://www.google.com/search?udm=50&aep=11
- Genspark - https://www.genspark.ai/
- Huggingchat - point of interesting being Cohere Command R - https://huggingface.co/chat/
- Kimi - https://www.kimi.com
- Le Chat - https://chat.mistral.ai/chat
- Mercury Playground - https://chat.inceptionlabs.ai/ -> Diffusion LLM test
- z.ai - https://chat.z.ai/
  - https://docs.z.ai/api-reference/introduction [API]
- Qwen - https://chat.qwen.ai/
- DeepWiki - https://deepwiki.org/ - automagic github wiki overviews

## Robot Aggregators
- OpenRouter - https://openrouter.ai/ - Real ManyBots


## UI
- https://github.com/oobabooga/text-generation-webui

### Domained
- Geology Oracle - https://geologyoracle.com/

## Research Analysis
### Notebook LM
- https://notebooklm.google/
  - note says 300 sources with the paid version but seems to stop working at some stage with total content - e.g. if you put books in
### alphaXiv
- https://www.alphaxiv.org/ - Chat with arxiv
### sciarena
- https://sciarena.allen.ai/ - compare models for a research question

### Research
- https://github.com/SakanaAI/AI-Scientist-v2
- https://github.com/going-doer/Paper2Code

### Models
- https://huggingface.co/unsloth/DeepSeek-R1-Distill-Llama-8B-unsloth-bnb-4bit

### Tools
- Ollama https://ollama.com/search
- Llama.cpp https://github.com/ggml-org/llama.cpp
- llama-server 
1. Go to the [llama.cpp releases page](https://github.com/ggerganov/llama.cpp/releases)
2. Download the package matching your GPU:
   - **NVIDIA:** llama-<version>-bin-win-cuda-cu12.2.0-x64.zip (or whichever CUDA version matches your driver)
   - **AMD:** llama-<version>-bin-win-vulkan-x64.zip
3. Extract it — llama-server.exe is right there, no install needed
4. Run it:

   llama-server.exe -m your-model.gguf -ngl 99 --host 0.0.0.0 --port 8080

  -ngl 99 offloads all layers to GPU.

Prerequisites:
- **NVIDIA:** Make sure you have the CUDA toolkit (or at least the CUDA runtime DLLs) matching the release you
downloaded. Usually having up-to-date NVIDIA drivers is enough since they bundle the runtime.
- **AMD:** Vulkan drivers (typically included with AMD Adrenalin drivers).

That's it — no compilation, no WSL needed. Just extract and run.
 ▸ Time: 10s

- LLM https://github.com/simonw/llm [from Datasette]
- Opencode https://github.com/sst/opencode
    - https://github.com/sst/opencode/issues/1669 - using opencode and ollama
- Claude Code router - https://github.com/musistudio/claude-code-router

## Tools - Need Signup
- Gemini cli [current decent free use level]
- Cursor
- Copilot
- Copilot cli
- Amazon Q Developer
- kiro-cli


### Tool calling hack
- https://www.reddit.com/r/LocalLLaMA/comments/1jauy8d/giving_native_tool_calling_to_gemma_3_or_really/

### Papers
- Nondeterminism in inference - https://thinkingmachines.ai/blog/defeating-nondeterminism-in-llm-inference/



