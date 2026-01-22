# My GitHub Pages Journey

My personal blog about learning GitHub Pages and web development.

---

## How This Blog Works

This blog uses a **data-driven approach** - content is stored as Markdown files and automatically rendered when the page loads.

### File Structure

```
merinm488.github.io/
├── index.html    # Blog template with CSS and JavaScript
├── data.md       # Blog content in Markdown format
└── README.md     # This file
```

### How It Works

1. **`data.md`** contains all blog posts in Markdown format
2. **`index.html`** loads the `marked.js` library (converts Markdown to HTML)
3. **JavaScript** fetches `data.md` and renders it into the page

### Why Markdown?

- **Simpler than HTML** - `# Title` instead of `<h1>Title</h1>`
- **Easier to edit** - Focus on content, not code
- **More readable** - Plain text is easier to read than HTML tags

---

## Running Locally

To test changes locally, you need a local web server 

Start the server,then open: **http://localhost:8000**

### Stop the Server

Press `Ctrl + C` in the terminal

---

## Editing Content

To add or edit blog posts, simply edit `data.md`:

```markdown
## New Blog Post Title

*Date here*

Your blog content here...

**Bold text** and *italic text* are supported.

- List item 1
- List item 2

[Link text](https://example.com)
```

---

## Technologies Used

- **HTML5** - Page structure
- **CSS3** - Styling
- **JavaScript** - Fetch and render Markdown
- **marked.js** - Markdown to HTML converter (via CDN)
- **GitHub Pages** - Free hosting

---

## Live Site

Visit at: https://merinm488.github.io
