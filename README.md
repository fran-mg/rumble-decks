# rumble-decks

<br>

#### Each deck follows this schema:

```json
{
  "id": "deck-id",
  "name": "Deck Name",
  "category": "Category",
  "description": "Description",
  "difficulty": "Easy|Medium|Hard",
  "tags": ["tag1", "tag2"],
  "cards": [
    {
      "id": "card-id",
      "word": "WORD",
      "tabooWords": ["word1", "word2"],
      "charadesHint": "hint",
      "passwordHint": "one-word clue"
    }
  ]
}
```

### ⚠️ **Important:**

#### You must register all new `packs/<deck>.json` files in `decks-index.json`. Missing files will not appear for user download.

<br>
<br>

## Related Projects

- Core Game Engine: Check out the main multiplayer word game repository at [fran-mg/rumble-game](https://github.com).
