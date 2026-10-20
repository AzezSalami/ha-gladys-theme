# Gladys Theme for Home Assistant

Makes Home Assistant look like the [Gladys Assistant](https://gladysassistant.com) UI
(Tabler-style palette, flat white cards, thin borders, Source Sans Pro). Includes light and dark modes.

## Install with HACS

1. HACS → ⋮ → **Custom repositories** → add this repo, category **Dashboard** (Theme).
2. Download **Gladys Theme**.
3. Add to `configuration.yaml` (if not already present) and restart:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
4. Profile → **Theme** → select **Gladys** (light/dark follows your setting).

For the exact font, install "Source Sans Pro" (e.g. via a custom resource); otherwise a system font is used.

## Releases

Automatic: every push to `main` that changes the theme publishes a new release (patch bump).
Add `#minor` or `#major` to the commit message for a bigger bump.
