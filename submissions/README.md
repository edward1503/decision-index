# Submissions

| Board | Model | Weights | Run | Public score | Inference and hardware |
|---|---|---|---|---|---|
| vision | VISTA-4B-A | [model](https://huggingface.co/edward1503/VISTA-4B-A/tree/778bef8b2420fec0f456842a8faffd2f52924f33) | [results](https://huggingface.co/datasets/edward1503/VISTA-4B-A-decision-index/tree/923f7f94be7ca3b26ca9608fda4b22435c3572a4/runs/vista-a-v1) | 65.493670 (public 0.3, 12,210/12,210) | `vista_engine:VistaEngine`; `weights=adapter`; kit `25c6ec7b6b5f44a216c63c3a700de3a9c6d6699d`; RTX 5060 Ti 16GB; BF16 backbone + FP32 LoRA/readout; 1–4 images, native up to 1,638,400 pixels/image, 32,768 tokens, no truncation; fixed prompt/official continuation with uniform letter anchors for image-only options; private score and official latency pending. Full settings and reproduce command in model card. |
