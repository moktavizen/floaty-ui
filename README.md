# Floaty UI

Floating Mode for Zen Browser! This mod will turn Compact Mode into Floating Mode.

## Preview

![Floaty UI preview](./preview.png)

## Install

### Manual

1. Export your mod list from `Settings > Zen Mods > Export Mods`
2. Open the exported `json` and add the following

    ```json
    "mod-floaty-ui": {
      "id": "mod-floaty-ui",
      "name": "Floaty UI",
      "description": "Floating Mode for Zen Browser! This mod will turn Compact Mode into Floating Mode.",
      "homepage": "https://github.com/moktavizen/floaty-ui",
      "style": "https://raw.githubusercontent.com/moktavizen/floaty-ui/refs/heads/main/mod-floaty-ui/chrome.css",
      "preferences": "https://raw.githubusercontent.com/moktavizen/floaty-ui/refs/heads/main/mod-floaty-ui/preferences.json",
      "readme": "https://raw.githubusercontent.com/moktavizen/floaty-ui/refs/heads/main/mod-floaty-ui/README.md",
      "image": "https://raw.githubusercontent.com/moktavizen/floaty-ui/refs/heads/main/preview-store.png",
      "author": "moktavizen",
      "version": "1.0.0",
      "tags": [],
      "createdAt": "2025-06-29",
      "updatedAt": "2025-06-29",
      "enabled": false
    }
    ```

    The structure should be like this

    ```json
    {
      "other-mods": {
        // other mods info
      }, // don't forget the comma before
      "mod-floaty-ui": {
        // floaty-ui info
      }
    }
    ```

3. Open your [`profile folder`](https://docs.zen-browser.app/guides/live-editing#step-1-access-the-profile-folder)
4. Replace the content of `zen-theme.json` with the content of the exported `json`
5. Open your [`chrome folder`](https://docs.zen-browser.app/guides/live-editing#step-2-create-the-chrome-folder)
6. Copy and paste `mod-floaty-ui folder` into `zen-themes folder`
7. Restart Zen Browser
8. Enable the mod from `Settings > Zen Mods`

## Uninstall

1. Go to `Settings > Zen Mods > Remove Theme`
