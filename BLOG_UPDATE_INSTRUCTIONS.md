# Weekly Blog Update Instructions

## When the user provides a new weekly blog entry, follow these steps AUTOMATICALLY:

### 1. Add to updates.html
- Place the new entry at the TOP of the `<section class="updates-list">` section
- Format as an `<article class="update-card">` with:
  - `<h2>` for the title
  - `<h3>Week X Journal Entry</h3>`
  - `<p class="date">Date</p>`
  - Content in `<p>` tags
- The CSS already has `margin-bottom: 3rem` on `.update-card` for spacing

### 2. Update index.html
- Add new entry at the TOP of the Recent Updates section
- Format as:
```html
<div class="update-card">
    <h3>Week X - Title</h3>
    <p class="date">Posted on [Date]</p>
    <p>[Brief preview of content - 2-3 sentences]</p>
    <a href="updates.html" class="read-more">Read full entry →</a>
</div>
```
- Keep the previous week's entry below it

### 3. Commit and Push to GitHub
```powershell
cd "c:\ReactGitEC2\IS490 Blog"
git add .
git commit -m "Add Week X blog entry"
git push
```

### 4. Open the browser
- Use open_simple_browser with: https://aprilv.github.io/IS490-Blog/

## DO ALL OF THIS IN ONE GO - DON'T ASK, JUST DO IT.

The user gives you the blog content → You add it everywhere → Push to GitHub → Open browser → Done.
