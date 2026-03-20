the girl vault

Pinterest-style link board for things you want to buy later. No account. No friction. Just paste.

##
[Live website](https://tanvi1505.github.io/girl-vault)
##

The problem
You're scrolling. You find a bag you love. You're not buying it right now, maybe you're waiting for payday, maybe you just want to think about it. So what do you do? 

Add to cart? You either impulse buy it or forget it's there.
Pinterest? It saves the aesthetic, not the actual link to purchase.
Notes app? You'll never find it again.
Browser bookmarks? That folder has 400 links and zero organization.

There's no dedicated space for "I want to buy this at some point", so I built one.

------------------------------

What it does
Paste a link. It's saved. That's the whole interaction.
Behind the scenes, it fetches the page title and preview image automatically — so your vault actually looks like a Pinterest board, not a graveyard of URLs. No extra steps required from you.
Collections let you organize on your own terms. There are no preset categories. You create what makes sense to you — Dresses, February Wishlist, Things I Can't Afford But Still — whatever. Everything you haven't sorted yet lives in Unsorted, exactly like Raindrop.io handles it.

How to use it
Option 1 — Download and open locally
The entire app is one HTML file. Download it, open it in any browser, start saving links. Your data stays in browser storage — it's there every time you reopen the file. No internet required after the first load.
1. Download index.html from this repo
2. Double-click to open in your browser
3. Paste links. Done.
Option 2 — Fork and deploy on GitHub Pages (free)
1. Fork this repo
2. Go to Settings → Pages → Source: main branch
3. Your vault is live at yourusername.github.io/girl-vault
Bookmark it on your phone's home screen and it works like a native app.

How collections work
Every saved link starts in Unsorted. From there:

Click the collection pill at the bottom of any card
A dropdown shows your existing collections
Select one to move the card — or hit "Create collection" right from the dropdown
Type a name, hit Create — the card moves there automatically

The sidebar shows all your collections with item counts. Click any to filter the view.

----------------------------------

Tech
Single index.html file — no framework, no build step, no backend, no tracking.

Vanilla JS + CSS
localStorage for persistence — your data never leaves your browser
allorigins.win proxy to fetch OG images and titles from saved links
Works fully offline after first load

------------------------------------

Why I built this
I'm a Data Science student, most of my work lives in Python, model training, and pipelines. This is a side project built because I had the actual problem and none of the existing apps solved it the right way.
Sometimes the most useful thing you can build is the small, specific tool that solves exactly one thing well.
If you found this useful, a star on the repo goes a long way. And if you're also a student putting things on GitHub for fun: keep going, it's worth it.

Built by Tanvica Samudrala
