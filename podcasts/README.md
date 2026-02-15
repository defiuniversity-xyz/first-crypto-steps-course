# First Crypto Steps - Podcasts

This folder contains 12 podcast files (`.m4a`) for upload to Google Cloud Storage. The upload script (`tools/upload_media.py`) reads from here directly—no moving or renaming required.

**File format:** `lessonN Title_With_Underscores.m4a` (e.g., `lesson1 Crypto_exchanges_are_gateways_not_banks.m4a`). The script extracts the lesson number and uploads to GCS at `lesson-NN/audio/`.
