# Google Sites Code Lines

Google Sites doesn't support Tables or Markdown, this script allows you to write Markdown inside a HTML snippet within Google Sites.

## Usage

1. While editing a Google Site page double click to bring up the page options
2. Select `<> Embed`
3. Change to the `Embed Code` tab
4. Paste the code below from the example 
5. Add your code in the `// PASTE YOUR CODE HERE` section
6. save

## Code snippets with Color Highlighting

If you wish to use code snippets with color highlighting in Google sites:

```typescript
<link href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism-tomorrow.min.css" rel="stylesheet" />
<style>
  pre[class*="language-"] {
    background: #1e1e1e !important;
    border: 1px solid #3c3c3c;
    border-radius: 8px;
    padding: 20px !important;
    margin: 10px 0;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  }
  code[class*="language-"], pre[class*="language-"] {
    text-shadow: none !important;
    font-family: 'Consolas', 'Monaco', monospace !important;
    font-size: 14px !important;
  }
</style>

<pre class="language-js"><code>

// PASTE YOUR CODE HERE

</code></pre>

<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-python.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-javascript.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-css.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-markup.min.js"></script> 
<script src="https://cdn.jsdelivr.net/gh/MikeDanielX/Google-sites-code-lines@main/index.js"></script>

<script>
  // This triggers the highlighting and the line numbers DO NOT REMOVE
  setTimeout(() => {
    Prism.highlightAll();
  }, 100);
</script>
```

## Code snippets (Color black / Simple Text)

If you wish to use code snippets in your Google Site as a Simple Text

```typescript
<script src="https://cdn.jsdelivr.net/gh/MikeDanielX/Google-sites-code-lines@main/index.js"></script>

<script>
markdown`
\`\`\`

[YOUR CODE]

\`\`\`
`
</script> 
```
## Example

If you wish to use code snippets with color highlighting in Google sites:

```typescript
<link href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism-tomorrow.min.css" rel="stylesheet" />
<style>
  pre[class*="language-"] {
    background: #1e1e1e !important;
    border: 1px solid #3c3c3c;
    border-radius: 8px;
    padding: 20px !important;
    margin: 10px 0;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  }
  code[class*="language-"], pre[class*="language-"] {
    text-shadow: none !important;
    font-family: 'Consolas', 'Monaco', monospace !important;
    font-size: 14px !important;
  }
</style>

<pre class="language-js"><code>

async function getTodoData() {
  const response = await fetch('https://jsonplaceholder.typicode.com/todos/1');
  const data = await response.json();
  console.log(data);
}

</code></pre>

<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-python.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-javascript.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-css.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-markup.min.js"></script> 
<script src="https://cdn.jsdelivr.net/gh/MikeDanielX/Google-sites-code-lines@main/index.js"></script>

<script>
  
  setTimeout(() => {
    Prism.highlightAll();
  }, 100);
</script>
