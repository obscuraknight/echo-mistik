# Upload Safety Checklist

Before making this repository public on GitHub:

1. Run:
   ```bash
   git status
   ```
   and confirm only intended files are staged.

2. Confirm there are no API keys:
   - no `gsk_...`
   - no `sk-...`
   - no `xai-...`
   - no `.env` file

3. Confirm local generated memory files are not committed:
   - `echo_long_memory.json`
   - `echo_dreams.json`

4. Confirm private Mistik code is not included.

5. Confirm you own or have permission to publish all images in `assets/`.

6. Keep:
   - `LICENSE`
   - `COMMERCIAL-LICENSING.md`
   - `README.md`

The public release is **source-available for non-commercial use**, not OSI open source.
