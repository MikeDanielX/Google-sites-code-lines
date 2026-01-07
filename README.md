# Google Sites Markdown

Google Sites doesn't support Tables or Markdown, this script allows you to write Markdown inside a HTML snippet within Google Sites.

## Usage

1. While editing a Google Site page double click to bring up the page options
2. Select `<> Embed`
3. Change to the `Embed Code` tab
4. Paste the code below from the example and replace Markdown with your own
5. Save

## Code snippets

If you wish to use code snippets inside your markdown, you'll need to escape the backticks:

```typescript
\`\`\`typescript
function getBestHero(Kamen_Rider: string): boolean {
  return true
}

const isKamenRiderTheBestHero = getBestHero('Kamen rider')
\`\`\`
```

## Example

```html
<script src="https://cdn.jsdelivr.net/gh/tutts/google-sites-markdown/index.js"></script>

<script>
markdown`
# Kamen Rider

Look I can write Markdown in Google Sites!

> Henshin?

- [X] Yeah!
- [ ] No

## Hero Table

| ID  | Name           | Hero               |
| --- | -------------- | ------------------ |
| 1   | Kouta Kazuraba | Kamen Rider Gaim   | 
| 2   | Sougo Tokiwa   | Kamen Rider Zi-O   |

*What about lists?*

- Yeah
- Hooray! 🎉
`
</script> 
```
