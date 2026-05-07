# Sprint 001 - Root Search MVP

## Goal

Create a simple root search function.

Users can:

- search root
- view meanings
- view related words

---

# Frontend

Vue.js

Page:

- input box
- result area

---

# Backend

ASP.NET Core API

API:

GET /api/roots/{root}

Response:

```json
{
  "root": "spect",
  "meaning": "look",
  "words": [
    "inspect",
    "respect"
  ]
}
```

---

# Database

Tables:
- roots
- words

---

# roots table defination
See the following design document for details.

```txt
docs/Sprint001/Database.md
```
# words table defination
See the following design document for details.

```txt
docs/Sprint001/Database.md
```


# Test Items

- root search works
- API response correct
- frontend display correct

---

# Future Improvement

- multilingual support
- audio
- GIF
- learning progress