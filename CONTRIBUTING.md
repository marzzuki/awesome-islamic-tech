# 📝 Contributor Instructions
## 🔹 Step 1: Add a human-friendly line

```md
- **[Name](URL)** · short neutral description. Site · _tags: quran, web, audio_
```

<br>

## 🔹 Step 2: Add the hidden YAML block

Right after the line, add this structured block inside an HTML comment (it won’t show on GitHub, but the site can read it):

```md
<!--
item:
  id: kebab-case-unique-id
  name: Name
  category: Must match the section heading
  description: Short one-liner (<=120 chars)
  links:
    site: https://...
    repo: https://...
    docs:
  tags: [tag1, tag2, tag3]
  languages: [JavaScript, Python]
  license: MIT|GPL|proprietary|mixed|unknown
  status: active|archived|wip
  added: YYYY-MM-DD
  updated:
-->
```

<br>

## 📏 Rules for contributions

* ✍️ Keep the **human line** under \~120 characters.
* 🔤 **Alphabetize** entries within each category.
* 🏷️ Use **lowercase tags**; prefer this controlled set:
  `quran`, `hadith`, `prayer-times`, `fiqh`, `charity`, `api`, `library`, `dataset`, `web`, `mobile`, `nlp`, `education`, `accessibility`.
* 🆔 `id` must be unique across the file (`kebab-case`).
* 🚫 Omit empty fields (don’t leave dummy placeholders).
