# Readme

## 特殊記法

- `__SUBJECT_HERE__`で主役のトークン位置を指定
- `__NEG...__`以下にペアとなるネガティブプロンプトを記述

## 生成用 JSON

以下ののワークフローで機能する.

- wildcard with Lora.json
- img2img with Lora.json

### 必要ノード

以下のノードが必要.

- ComfyUI Impact Pack
- ComfyUI-Custom-Scripts
- WAS Node Suite (Revised)
- advanced_load_image, advanced_save_image.py (`https://github.com/function2706/comfyui-mynodes.git`)

advanced_load/save_image は `ComfyUI\custom_nodes` に clone すること.
