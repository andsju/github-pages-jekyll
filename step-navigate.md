# Navigera mellan sidor

En fil med namnet `index.md` eller `index.html` visas automatiskt i sidans rootkatalog. För att visa fler sidor på webbplatsen skapar du sidor som är uppbyggda på samma sätt som `index.md`. Namnet på sidan kommer bli den sökväg som du anger i url:en.


Skapa sida med namnet `about.md` (ex genom att göra en kopa av `index.md`).

```markdown
---
title: Om
layout: default
---

# Om
En webbplats som visar hur Jekyll kan användas.

```

Navigera till `http://localhost:4000/about` så kommer sidan att visas.

## Meny för navigering
I `header.html` kan du nu lägga in ett nav element för navigering mellan sidor.

```markdown
<header>
    My site header
</header>
<hr>
<nav>
    <a href="/">Start</a> | <a href="/about">Om</a>
 </nav>
```
