# COCO Mask Generator

This project generates binary or multi-class segmentation masks from the COCO dataset using the official annotations.

## Features
- Converts COCO annotations to masks.
- Supports both binary and multi-class masks.
- Handles overlapping regions, missing annotations, and `iscrowd` flags.

## Installation

Install dependencies using `uv` (universal virtual environment):

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
