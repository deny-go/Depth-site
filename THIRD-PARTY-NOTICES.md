# Third-party components

- **Depth Anything V2 Small** — Lihe Yang et al.; Apache-2.0. https://github.com/DepthAnything/Depth-Anything-V2. ONNX conversion: https://huggingface.co/onnx-community/depth-anything-v2-small, revision 4472b7362082ad9968fee890ca0f1e5aca36b93d. License: MODEL-LICENSE.txt.
- **Transformers.js 3.8.1** — Hugging Face; Apache-2.0. https://github.com/huggingface/transformers.js. The installed package license is included in licenses/transformers-LICENSE.txt in the production build.
- **ONNX Runtime Web** — Microsoft Corporation; MIT. https://github.com/microsoft/onnxruntime. Version is pinned transitively in pnpm-lock.yaml to the version required by Transformers.js. License: licenses/onnxruntime-LICENSE.txt in the production build.
- **fflate 0.8.2** — Arjun Barrett; MIT. https://github.com/101arrowz/fflate. The installed package license is included in licenses/fflate-LICENSE.txt in the production build.

Vite is a development-only build dependency. Model weights are downloaded separately by the visitor, not committed or bundled with this website.
