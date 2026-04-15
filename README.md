# AI Character Concept Art Generation (CA6114 Scenario 3)

This repository contains the setup, execution scripts, and reporting documents for the CA6114 Part 3 Assignment (Scenario 3). The core objective was to utilize advanced ComfyUI workflows, LoRA training, IPAdapter FaceID, and Inpaint to seamlessly blend artistic styles and generate consistent character concept art.

## ⚠️ Compliance & Disclaimer

**Academic & Non-profit Use Only**: All methodologies, processes, and outputs generated in this project act as an academic, non-commercial proof-of-concept under **Fair Use**. The aesthetic representations and textual references utilized for the model's style training are strictly modeled after **The Art of Death Stranding**. The original artwork, intellectual properties, and character conventions are solely owned by **Kojima Productions** and **Sony Interactive Entertainment**.  

**Repository Exclusions (For Compliance)**:
- 🚫 **Training Data**: The raw `train_data`, which sourced scanned pages from commercial publications, is **not uploaded** to this public repository to prevent copyright infringement.
- 🚫 **Trained Models**: High-capacity LoRA weights (`death_stranding_style.safetensors`) and other model checkpoints are excluded due to large file sizes and licensing limitations.

## Repository Structure

- `CA6114_Part3_Report.docx` - The finalized formal report detailing architecture, training parameters, workflow setups, and comparison analyses.
- `CA6114_Part3_完整执行记录_最终版.md` - (Sanitized) A comprehensive logging file for setup configurations and pipeline limits.
- `comfyui-6114 (1).ipynb` - (Sanitized) The deployment Notebook for instantiating ComfyUI and its extensions on cloud GPUs.
- `comfyui-train (1).ipynb` - Notebook for training the Kohya sd-scripts LoRA.
- `download-clip-vision-h.ipynb` / `notebook (1).ipynb` - Scripts to download necessary checkpoint models.
- `Workflow*.json` (if any) - ComfyUI graph setups used in this project.
