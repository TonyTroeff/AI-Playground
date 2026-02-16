# AI Playground — experiments with small AI tasks 🚀

A lightweight repository for experimenting with AI workflows. Comes with example notebooks, a local Hugging Face model cache, and simple utilities so you can iterate fast.

## Quick start

1. Install dependencies:
    - CPU:
        ```bash
        pip install -r requirements_base.txt
        pip install -r requirements_torch.txt
        ```
    - GPU (CUDA-matched):
        ```bash
        pip install -r requirements_base.txt
        pip install -r requirements_torch_cuda130.txt
        ```

2. Run the notebooks you are interested in.

## Notes & troubleshooting

- Models in `models/huggingface/` are large — remove or re-download as needed.
- For GPU use, ensure your installed `torch` matches your CUDA version (see `requirements_torch_cuda130.txt`).

## License

This repository is licensed under the [MIT License](LICENSE).

Happy experimenting! 💡
