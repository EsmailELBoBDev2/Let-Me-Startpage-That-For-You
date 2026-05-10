# Let Me Startpage That For You 🔍

A clone of the classic [lmgtfy.com](https://lmgtfy.com) — but privacy-first, using **Startpage** instead of Google. Single HTML file, zero dependencies.

> 🤖 **Built entirely with AI** — [Antigravity](https://antigravity.dev) (Google DeepMind) via a few short prompts.

---

## 💬 Prompts Used

Here's exactly what I typed to build this, start to finish:

```
1. Can you create an equivalent let me google that website? and it uses startpage
   instead of google search — make it simple like only HTML, CSS and JS

2. I want it like same animation of let me google that — when i search something
   it gives URL with my query, and the animation plays when someone opens the link

3. Make 'was that so hard' bigger and more noticeable but match the theme —
   also make it dark themed like startpage not white

4. Add a footer that says it uses startpage because it doesn't track you like
   google and you get the same results — short, sweet, direct, fits the site

5. Make the footer font color brighter but still match the site style — and say
   we use startpage but we're not affiliated, keep their trademark clear

6. Add the project github url and say its FOSS — match the site style,
   short sweet direct, put it where it makes sense

7. Add the rest of prompts in readme then do a push again
```

Seven prompts → one working project.

---

## ⚙️ How It Works

The whole thing is one `index.html` file with two modes:

**Generator mode** (no query in URL)
- You type what someone should've searched
- Click **Make Link** → get a shareable URL like `index.html?q=how+to+google`
- Copy & send it to them

**Player mode** (URL has `?q=something`)
- A fake mouse cursor glides onto the screen
- It clicks the search box → text types in letter by letter (with random human-like delays)
- Cursor moves to the Search button → clicks it
- *"Was that so hard? 🙄"* pops in
- Page redirects to Startpage with the query

No frameworks. No build step. No tracking. Just HTML + CSS + ~80 lines of JS.

---

## 🚀 Usage

Just open `index.html` in a browser. No server needed.

```
git clone https://github.com/EsmailELBoBDev2/Let-Me-Startpage-That-For-You
cd Let-Me-Startpage-That-For-You
# open index.html in your browser
```

Or host it anywhere static (GitHub Pages, Netlify, Cloudflare Pages, etc.) and the shareable links will work perfectly.

---

## 🔒 Why Startpage?

Because Google tracks you. [Startpage](https://www.startpage.com) gives you Google results without the surveillance. Felt like the right fit for a "let me search that for you" tool that isn't ironic about privacy.
