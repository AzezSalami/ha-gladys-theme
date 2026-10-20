# Gladys Theme for Home Assistant

Makes Home Assistant look like the [Gladys Assistant](https://gladysassistant.com) UI
(pastel gradient background, frosted-glass rounded cards, navy pills, mint-green actions).

## Install with HACS

1. HACS → ⋮ → **Custom repositories** → add this repo, category **Dashboard** (Theme).
2. Download **Gladys Theme**.
3. Add to `configuration.yaml` (if not already present) and restart:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
4. Profile → **Theme** → select **Gladys** (light/dark follows your setting).

For the exact font, install "Inter" (e.g. via a custom resource); otherwise a system font is used.

## Releases

Edit `VERSION` and push to `main`. If `v<VERSION>` doesn't exist yet, a release is created automatically.
