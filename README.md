# LoRA Training Project for SDXL (TOK Home)

This is a LoRA training project for Stable Diffusion XL 1.0 with TOK Home architectural image dataset, applying CSD (Semantic Richness) technique to improve caption quality.

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