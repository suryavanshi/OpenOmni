# OpenOmni
An Open Source Project to develop a model with capabilities similar to GPT-4o or GPT-4 Omni

## Relevant Papers
- **Vision + Text Models**
  - [Chameleon from Meta](https://ai.meta.com/blog/generative-ai-text-images-cm3leon/)
  - [LLava Family of Models](https://llava-vl.github.io/)
  - [CogVLM](https://arxiv.org/abs/2311.03079)
  - [Flamingo (from DeepMind)](https://deepmind.google/discover/blog/tackling-multiple-tasks-with-a-single-visual-language-model/)
 
## Audio + Text LLM
[Mini-omni](https://github.com/gpt-omni/mini-omni)

## Comparing Various Vision Language Models
| Model       | Params | Base Language Model                                        | Vision Encoder                        | Max Input Resolution          | Apache/MIT             |
|-------------|--------|-------------------------------------------------------------|---------------------------------------|-------------------------------|------------------------|
| LLaVA-v1    | 7B     | <span style="color:blue">LLaMA-2-7B-Chat</span> &#128101;   | <span style="color:green">CLIP ViT-L/14</span> &#128248;            | <span style="color:purple">224x224</span> &#128200;          | <span style="color:red">No</span> &#10060;         |
| LLaVA-1.6   | 7B     | <span style="color:blue">Mistral-7B-Instruct-v0.2 a</span> &#128101; | <span style="color:green">CLIP ViT-L/14</span> &#128248;            | <span style="color:purple">336x336</span> &#128200;          | <span style="color:red">Yes</span> &#9989;         |
| IDEFICS-2   | 8B     | <span style="color:blue">Mistral-7B-v0.1</span> &#128101;   | <span style="color:green">siglip-so400m</span> &#128248;            | <span style="color:purple">224x224</span> &#128200;          | <span style="color:red">Yes</span> &#9989;         |
| OpenVLA     | 7B     | <span style="color:blue">Llama 2 7B</span> &#128101;        | <span style="color:green">SigLIP + DINOv2</span> &#128248;          | <span style="color:purple">224x224</span> &#128200;          | <span style="color:red">No</span> &#10060;         |
| CogVLM2     | 19B    | <span style="color:blue">Llama-3-8B-Instruct</span> &#128101;| <span style="color:green">EVA2-CLIP-E</span> &#128248;              | <span style="color:purple">1344 x 1344</span> &#128200;      | <span style="color:red">No</span> &#10060;         |
| MiniCPM-V   | 8B     | <span style="color:blue">Llama-3-8B-Instruct</span> &#128101;| <span style="color:green">SigLip-400M</span> &#128248;              | <span style="color:purple">224x224</span> &#128200;          | <span style="color:red">No</span> &#10060;         |
| PaLI-GEMMA  | 3B     | <span style="color:blue">Gemma 2B</span> &#128101;          | <span style="color:green">SigLIP-So400</span> &#128248;             | <span style="color:purple">896x896</span> &#128200;          | <span style="color:red">No</span> &#10060;         |
| ShareGPT4V  | 7B     | <span style="color:blue">Vicuna-1.5-7B</span> &#128101;     | <span style="color:green">CLIP ViT-L/14</span> &#128248;            | <span style="color:purple">336x336</span> &#128200;          | <span style="color:red">No</span> &#10060;         |
