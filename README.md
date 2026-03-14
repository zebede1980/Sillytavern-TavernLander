# Another Character Library

An SillyTavern extension that replaces the default landing page with a rich character library view.

## Disclaimers

- This project is vibe coded.
- Mobile support is not working properly yet.

## Features

- Replaces the default empty-chat landing page with a full-screen character library.
- Searches across character names, SillyTavern built-in tags, Creator's Notes, creator name, version, and first message.
- Sorts by `A-Z`, `Z-A`, `Recently Added`, `Added First`, and `Recently Chatted`.
- Provides `All Characters` and `Favourite Characters` library tabs.
- Supports page-size controls for `12`, `24`, `48`, and `96`.
- Uses SillyTavern's built-in tag system for card display and edit-mode tag assignment.
- Shows card avatars, titles, Creator's Notes previews, built-in tag badges, a favourite star badge, and a card menu with `Favourite`, `Edit`, and `Delete`.
- Opens a detail modal with a larger image, first message, built-in tags, creator link, quick chat, favourite, and delete actions.
- Includes an edit tab for Creator's Notes, creator name, version, creator link, first message, and built-in tag assignment.
- Uses a separate favourites system from SillyTavern's built-in favourites, so you can keep an even smaller personal shortlist there.
- Adapts styling from SillyTavern theme variables.

## Images

![image](https://i.imgur.com/ANDlGoh.png)
![image](https://i.imgur.com/fs1Yw4A.png)

## Install

Install it through SillyTavern's built-in extension installer from the repository URL:

```text
https://github.com/ayvencore/SillyTavern-Lorebook-Manager
```

## Notes

- Descriptions prefer `Creator's Notes` data from the character card.
- The library reads tags from SillyTavern's built-in tag system, not from card-embedded tag fields.
- The library favourites are separate from SillyTavern's built-in favourites.
- Edit-mode saves are defensive: the extension updates local overrides and also attempts to call compatible SillyTavern save APIs.
- SillyTavern internals can vary by version, so some method names in [index.js](C:/dev/ST/Sillytavern-Another-Character-Library/release/Sillytavern-Another-Character-Library/index.js) may still need small adjustments after live testing.
