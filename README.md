# ShengHui Models

License, attribution, and checksum inventory for the MOSS pack used by the [ShengHui](https://github.com/BigLazyET/ShengHui) Mac app. The app downloads the pinned MLX 8-bit weights from Hugging Face. This repository is not a download source.

## MOSS-Transcribe-Diarize 0.9B (MLX 8-bit)

- Original model: OpenMOSS / MOSI.AI — https://github.com/OpenMOSS/MOSS-Transcribe-Diarize
- MLX conversion: vanch007 — https://huggingface.co/vanch007/mlx-MOSS-Transcribe-Diarize-8bit
- Model ID: `vanch007/mlx-MOSS-Transcribe-Diarize-8bit`
- Pinned revision: `7210aef739be6b9e068fba9b1d60369ec053655b`
- License: Apache-2.0; see LICENSE and NOTICE.txt.
- Nine runtime files, exact sizes, and SHA-256 hashes in manifest.json are the source of truth for the pack contents (1,269,855,425 bytes).

The app downloads each file from `https://huggingface.co/vanch007/mlx-MOSS-Transcribe-Diarize-8bit/resolve/7210aef739be6b9e068fba9b1d60369ec053655b/<filename>` (the same path on `https://hf-mirror.com`). When the system region is CN, it tries `https://hf-mirror.com` first; otherwise it tries `https://huggingface.co` first. If the first host fails, or a mirror redirect leaves hf-mirror.com, the app tries the other host once.

`repository` and `releaseTag` in manifest.json identify the historical GitHub Release `moss-0.9b-8bit-7210aef`. That release is not the app's download source. Weight files are not stored in Git. This repository contains no application source, user recordings, videos, or transcripts.

Speaker labels are anonymous; users still need to review text, timing, and character assignments.
