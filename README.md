# MSCG-Diff dataset
## Project Profile
This repository is used for presentations on the MSCG-Diff dataset. Here, we have uploaded 50 images within the MSCG-Diff
dataset, along with the corresponding text descriptions.

# MSCG-Diff
Generating high-quality Chinese calligraphic characters poses a significant challenge, particularly in few-shot learning scenarios where the scarcity of calligraphy data further exacerbates the difficulty. Existing generative models (e.g., GANs and diffusion models) often encounter issues such as stroke omission, misalignment, artifacts, and style ambiguity when generating Chinese handwritten characters. Moreover, the inherent diversity of stylistic content and complexity of brushwork techniques in Chinese calligraphy present additional challenges for generation quality.

To address these limitations, this paper proposes a Multi-Style Chinese calligraphy Generation Diffusion model (MSCG-Diff) with error correction mechanisms. Our approach enhances the generation process through two key interactive mechanisms: First, we employ style references and high-frequency style information obtained through specialized filters to provide style constraints, while utilizing an iterative skeleton extraction network to capture structural features and ensuring character correctness through standard Chinese font library mapping. Second, we introduce a multi-feature fusion module that hierarchically integrates various features and repeatedly injects skeleton features at different levels of the U-Net architecture to guide the diffusion model in achieving content-style integration during preliminary learning.

Furthermore, we incorporate a Recognition-Error Correction (REC) module for subsequent fine-tuning, which performs real-time recognition and correction of generated characters to ensure output accuracy and consistency. Additionally, we have constructed the Chinese Handwriting Character dataset (CHC), comprising over 50,000 high-quality single-character calligraphy images across 11 categories. This dataset, specifically designed for Chinese calligraphy research, was meticulously annotated through OCR tools and manual verification to support model training.

Extensive experimental results demonstrate that MSCG-Diff can effectively generate structurally complex Chinese calligraphic characters under few-shot conditions, while exhibiting superior performance in maintaining glyph accuracy and generalizing to unseen character generation.

# code
We will upload the training as well as the test code and the full dataset at an appropriate time!
