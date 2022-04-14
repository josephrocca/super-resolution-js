# Image upscaling/super-resolution with JS/ONNX/WebAssembly
SOTA image super-resolution running in the browser with an ONNX-ported [SwinIR](https://github.com/JingyunLiang/SwinIR) model. All credit goes to Jingyun Liang and the other authors of SwinIR.

**Try it here**: https://josephrocca.github.io/super-resolution-js

![2318cbb8-123f-48bf-9322-09789538cd47](https://user-images.githubusercontent.com/1167575/163460977-b5ba032a-e122-472c-b8fd-d3e4920fbb06.jpg)

Notes:
 * Model file in demo is served from [this Hugging Face repo](https://huggingface.co/rocca/swin-ir-onnx), and that repo also has instructions on porting the model to ONNX.
 * Should work in Deno too, but I haven't tested.
