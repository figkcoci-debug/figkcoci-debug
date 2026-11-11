# figkcoci

Mobile AI, ternary quantization, C++ and Rust.

I build tools for running large language models on phones.

- [PEHT](https://github.com/figkcoci-debug/peht) folded Hadamard ternary 27B models on Android, 13x faster than the vendor PQ2_0 path at the same quality
- [phone-cluster](https://github.com/ggarembroo/phone-cluster) one local LLM across two Android phones over USB with ggml-rpc
- upstream work in [llama.cpp](https://github.com/ggml-org/llama.cpp) Vulkan device fault handling and ggml-rpc reliability

Focused on ternary weights, phone memory bandwidth, and NPU/CPU scheduling.

[Main profile](https://github.com/ggarembroo) · [PEHT whitepaper](https://github.com/ggarembroo/peht-architecture-whitepaper)
