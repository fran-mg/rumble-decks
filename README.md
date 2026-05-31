# articulate-decks

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
