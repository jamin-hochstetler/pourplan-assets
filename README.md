# pourplan-assets

Public asset hosting for the PourPlan iOS app — the on-device model files the app downloads on first use.

## LaMa model (Clean Plate)

Release `lama-v1` carries `LaMa-stored.zip`: the LaMa inpainting model in CoreML form (`LaMa.mlmodelc`), repackaged with ZIP "stored" (uncompressed) entries so the app's extractor copies the files directly, with no decompression step.

- Model: LaMa — https://github.com/advimman/lama — Apache License 2.0
- CoreML conversion by john-rocky (CoreML-Models); bundle mirrored from the xulihang/CoreMLaMa release
- File size: 216,855,606 bytes
- SHA-256: 983706255ff290de00c695a305a5e9f375dbc70fdffbb7db79b344c4650468b1
