# Meares Birthday Display

A 16:9 birthday screen for Yodeck, hosted with GitHub Pages.

## Files
- `index.html` – display logic
- `style.css` – Meares birthday design
- `birthday.json` – today's birthday data; this is the file Power Automate will update
- `assets/meares-logo.png` – company logo

## Test a birthday
Temporarily replace `birthday.json` with:

```json
{
  "birthdays": [
    {"name":"BAKOMIHALIS, NATASHA","date":"December 1"}
  ]
}
```

For multiple birthdays:

```json
{
  "birthdays": [
    {"name":"Employee One","date":"December 1"},
    {"name":"Employee Two","date":"December 1"}
  ]
}
```

Use `{ "birthdays": [] }` when there are no birthdays.

## GitHub Pages
Push these files to the repository, then open **Settings → Pages** and deploy from your main branch/root. Use the resulting Pages URL as the Yodeck Web Page URL.
