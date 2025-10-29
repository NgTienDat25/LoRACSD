# LoRA Training Project for SDXL (TOK Home)

This project fine-tunes Stable Diffusion XL 1.0 using a custom TOK Home architectural image dataset, applying the CSD (Semantic Richness) technique to enhance image quality and better align generated results with the dataset — even when prompts are low-quality, the dataset is small, and computational resources are limited.

## Scheduler Comparison (Same Seed/Prompt)

<table align="center">
  <tr>
    <td align="center"><strong>Output without CSD</strong></td>
    <td align="center"><strong>Output with CSD</strong></td>
  </tr>
  <tr>
    <td>
      <img src="output_xl_lora_withoutcsd.png" width="400">
    </td>
    <td>
      <img src="output_xl_lora_csd.png" width="400">
    </td>
  </tr>
</table>

## Installation

Install the required libraries:
```bash
pip install -r requirements.txt