
![image](https://raw.githubusercontent.com/mflux-community/mflux/refs/heads/Assets-MFlux-Community/mflux-community-logo.jpg)

[🤗 Hugging Face](https://huggingface.co/mflux-community)

MFlux is library for running generative AI image models (Flux.2, Z-Image, Krea, Ernie etc) locally on Apple Silicon Macs (and on Linux with CUDA). 
It allows users to generate images from text prompts via a simple CLI command `mflux-generate`. 
MFlux leverages Apple’s MLX framework - taking advantage of unified memory and Metal acceleration for efficient on-device inference.


|    Model    |   Variant   | Release Date | Size | Original Repo                                               | Q3 | Q4 | Q6 | Q8 | BF16 |
| :---------: | :---------: | :----------: | :--: | ----------------------------------------------------------- | :--: | :--: | :--: | :--: | :--: |
| Ideogram 4  |             |   Jun 2026   |  9B  | https://huggingface.co/ideogram-ai/ideogram-4-fp8           |  |  |  |  |  |
| Krea2 |  | Jun 2026 | 12B | https://huggingface.co/krea/Krea-2 | [⭐](https://huggingface.co/mflux-community/krea2-mflux-q3) | [⭐](https://huggingface.co/mflux-community/krea2-mflux-q4) | [⭐](https://huggingface.co/mflux-community/krea2-mflux-q6) | [⭐](https://huggingface.co/mflux-community/krea2-mflux-q8) | [⭐](https://huggingface.co/mflux-community/krea2-mflux-bf16) |
| Krea2 | Turbo | Jun 2026 | 12B | https://huggingface.co/krea/Krea-2-Turbo | - | [⭐](https://huggingface.co/mflux-community/krea-2-turbo-mflux-q4) | - | [⭐](https://huggingface.co/mflux-community/krea-2-turbo-mflux-q8) | - |
| ERNIE-Image | Base | Apr 2026 | 8B | https://huggingface.co/baidu/ERNIE-Image | [⭐](https://huggingface.co/mflux-community/ernie-image-base-mflux-q3) | [⭐](https://huggingface.co/mflux-community/ernie-image-base-mflux-q4) | [⭐](https://huggingface.co/mflux-community/ernie-image-base-mflux-q6) | [⭐](https://huggingface.co/mflux-community/ernie-image-base-mflux-q8) | [⭐](https://huggingface.co/mflux-community/ernie-image-base-mflux-bf16) |
| ERNIE-Image | Turbo | Apr 2026 | 8B | https://huggingface.co/baidu/ERNIE-Image-Turbo | [⭐](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q3) | [⭐](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q4) | [⭐](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q6) | [⭐](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q8) | [⭐](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-bf16) |
| Flux.2 | Klein 9B KV | Jan 2026 | 9B | https://huggingface.co/black-forest-labs/FLUX.2-klein-9b-kv | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q3) | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q4) | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q6) | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q8) | - |
| Flux.2 | Klein 9B | Jan 2026 | 9B | https://huggingface.co/black-forest-labs/FLUX.2-klein-9B | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q3) | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q4) | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q6) | [⭐](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q8) | - |
| Flux.2 | Klein 4B | Jan 2026 | 4B | https://huggingface.co/black-forest-labs/FLUX.2-klein-4B | [⭐](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q3) | [⭐](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q4) | [⭐](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q6) | [⭐](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q8) | - |
| Z-Image | Base | Nov 2025 | 6B | https://huggingface.co/Tongyi-MAI/Z-Image | - | - | [⭐](https://huggingface.co/mflux-community/z-image-base-mflux-q6) | [⭐](https://huggingface.co/mflux-community/z-image-base-mflux-q8) | [⭐](https://huggingface.co/mflux-community/z-image-base-mflux-bf16) |
| Z-Image | Turbo | Nov 2025 | 6B | https://huggingface.co/Tongyi-MAI/Z-Image-Turbo | [⭐](https://huggingface.co/mflux-community/z-image-turbo-mflux-q3) | [⭐](https://huggingface.co/mflux-community/z-image-turbo-mflux-q4) | [⭐](https://huggingface.co/mflux-community/z-image-turbo-mflux-q6) | [⭐](https://huggingface.co/mflux-community/z-image-turbo-mflux-q8) | [⭐](https://huggingface.co/mflux-community/z-image-turbo-mflux-bf16) |
|    FIBO     |             |  Oct 2025+   |  8B  | https://huggingface.co/briaai/FIBO                          |  |  |  |  |  |
| Qwen-Image  |             |  Aug 2025+   | 20B  | https://huggingface.co/Qwen/Qwen-Image                      |  |  |  |  |  |
| Qwen-Image  |    2512     |  Aug 2025+   | 20B  | https://huggingface.co/Qwen/Qwen-Image-2512                 |  |  |  |  |  |
| Qwen-Image  |   Layered   |  Aug 2025+   | 20B  | https://huggingface.co/Qwen/Qwen-Image-Layered              |  |  |  |  |  |
| Qwen-Image  |    Edit     |  Aug 2025+   | 20B  | https://huggingface.co/Qwen/Qwen-Image-Edit                 |  |  |  |  |  |
| Qwen-Image  |  Edit 2509  |  Aug 2025+   | 20B  | https://huggingface.co/Qwen/Qwen-Image-Edit-2509             |  |  |  |  |  |
| Qwen-Image  |  Edit 2511  |  Aug 2025+   | 20B  | https://huggingface.co/Qwen/Qwen-Image-Edit-2511            |  |  |  |  |  |
|   SeedVR2   |     3B      |   Jun 2025   |  3B  | https://huggingface.co/ByteDance-Seed/SeedVR2-3B            |  |  |  |  |  |
|   SeedVR2   |     7B      |   Jun 2025   |  7B  | https://huggingface.co/ByteDance-Seed/SeedVR2-7B            |  |  |  |  |  |
|  Depth Pro  |             |   Oct 2024   |  -   | https://huggingface.co/apple/DepthPro                       |  |  |  |  |  |
| Flux.1 Schnell |  |  | - | https://huggingface.co/black-forest-labs/FLUX.1-schnell | [⭐](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q3) | [⭐](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q4) | [⭐](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q6) | [⭐](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q8) | [⭐](https://huggingface.co/mflux-community/flux-1-schnell-mflux-bf16) |
| Flux.1 Dev |  |  | - | https://huggingface.co/black-forest-labs/FLUX.1-dev | [⭐](https://huggingface.co/mflux-community/flux-1-dev-mflux-q3) | [⭐](https://huggingface.co/mflux-community/flux-1-dev-mflux-q4) | [⭐](https://huggingface.co/mflux-community/flux-1-dev-mflux-q6) | [⭐](https://huggingface.co/mflux-community/flux-1-dev-mflux-q8) | [⭐](https://huggingface.co/mflux-community/flux-1-dev-mflux-bf16) |
