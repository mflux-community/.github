![image](https://raw.githubusercontent.com/mflux-community/.github/refs/heads/main/assets/mflux-community-logo.jpg)

[🤗 Hugging Face](https://huggingface.co/mflux-community)

MFlux is library for running generative AI image models (Flux.2, Z-Image, Krea, Ernie etc) locally on Apple Silicon Macs (and on Linux with CUDA). 
It allows users to generate images from text prompts via a simple CLI command `mflux-generate`. 
MFlux leverages Apple’s MLX framework - taking advantage of unified memory and Metal acceleration for efficient on-device inference.


| Model | Release Date | Size | Q3 | Q4 | Q6 | Q8 | BF16 |
| --- | ---------- | -- | :-: | :-: | :-: | :-: | :--: |
| **[Ideogram 4](https://huggingface.co/ideogram-ai/ideogram-4-fp8)** | Jun 2026 | 9B | | | | | |
| **[Krea2](https://huggingface.co/krea/Krea-2)** | Jun 2026 | 12B | **[Q3](https://huggingface.co/mflux-community/krea2-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/krea2-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/krea2-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/krea2-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/krea2-mflux-bf16)** |
| **[Krea2 Turbo](https://huggingface.co/krea/Krea-2-Turbo)** | Jun 2026 | 12B | | **[Q4](https://huggingface.co/mflux-community/krea-2-turbo-mflux-q4)** | | **[Q8](https://huggingface.co/mflux-community/krea-2-turbo-mflux-q8)** | |
| **[ERNIE-Image Base](https://huggingface.co/baidu/ERNIE-Image)** | Apr 2026 | 8B | **[Q3](https://huggingface.co/mflux-community/ernie-image-base-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/ernie-image-base-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/ernie-image-base-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/ernie-image-base-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/ernie-image-base-mflux-bf16)** |
| **[ERNIE-Image Turbo](https://huggingface.co/baidu/ERNIE-Image-Turbo)** | Apr 2026 | 8B | **[Q3](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/ernie-image-turbo-mflux-bf16)** |
| **[Flux.2 Klein 9B KV](https://huggingface.co/black-forest-labs/FLUX.2-klein-9b-kv)** | Jan 2026 | 9B | **[Q3](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/flux2-klein-9b-kv-mflux-q8)** | |
| **[Flux.2 Klein 9B](https://huggingface.co/black-forest-labs/FLUX.2-klein-9B)** | Jan 2026 | 9B | **[Q3](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/flux2-klein-9b-mflux-q8)** | |
| **[Flux.2 Klein 4B](https://huggingface.co/black-forest-labs/FLUX.2-klein-4B)** | Jan 2026 | 4B | **[Q3](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/flux2-klein-4b-mflux-q8)** | |
| **[Z-Image Base](https://huggingface.co/Tongyi-MAI/Z-Image)** | Nov 2025 | 6B | | | **[Q6](https://huggingface.co/mflux-community/z-image-base-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/z-image-base-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/z-image-base-mflux-bf16)** |
| **[Z-Image Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo)** | Nov 2025 | 6B | **[Q3](https://huggingface.co/mflux-community/z-image-turbo-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/z-image-turbo-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/z-image-turbo-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/z-image-turbo-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/z-image-turbo-mflux-bf16)** |
| **[FIBO](https://huggingface.co/briaai/FIBO)** | Oct 2025+ | 8B | | | | | |
| **[Qwen-Image](https://huggingface.co/Qwen/Qwen-Image)** | Aug 2025+ | 20B | | | | | |
| **[Qwen-Image 2512](https://huggingface.co/Qwen/Qwen-Image-2512)** | Aug 2025+ | 20B | | | | | |
| **[Qwen-Image Layered](https://huggingface.co/Qwen/Qwen-Image-Layered)** | Aug 2025+ | 20B | | | | | |
| **[Qwen-Image Edit](https://huggingface.co/Qwen/Qwen-Image-Edit)** | Aug 2025+ | 20B | | | | | |
| **[Qwen-Image Edit 2509](https://huggingface.co/Qwen/Qwen-Image-Edit-2509)** | Aug 2025+ | 20B | | | | | |
| **[Qwen-Image Edit 2511](https://huggingface.co/Qwen/Qwen-Image-Edit-2511)** | Aug 2025+ | 20B | | | | | |
| **[SeedVR2 3B](https://huggingface.co/ByteDance-Seed/SeedVR2-3B)** | Jun 2025 | 3B | | | | | |
| **[SeedVR2 7B](https://huggingface.co/ByteDance-Seed/SeedVR2-7B)** | Jun 2025 | 7B | | | | | |
| **[Depth Pro](https://huggingface.co/apple/DepthPro)** | Oct 2024 | - | | | | | |
| **[Flux.1 Schnell](https://huggingface.co/black-forest-labs/FLUX.1-schnell)** | | - | **[Q3](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/flux-1-schnell-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/flux-1-schnell-mflux-bf16)** |
| **[Flux.1 Dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)** | | - | **[Q3](https://huggingface.co/mflux-community/flux-1-dev-mflux-q3)** | **[Q4](https://huggingface.co/mflux-community/flux-1-dev-mflux-q4)** | **[Q6](https://huggingface.co/mflux-community/flux-1-dev-mflux-q6)** | **[Q8](https://huggingface.co/mflux-community/flux-1-dev-mflux-q8)** | **[BF16](https://huggingface.co/mflux-community/flux-1-dev-mflux-bf16)** |

