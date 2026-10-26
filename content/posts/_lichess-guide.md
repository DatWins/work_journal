---
title: "Lichess Embed Guide"
date: 2026-10-26
draft: true
tags:
  - guide
categories: ["guide"]
---
<!--
LICHESS EMBED CHEAT SHEET
Keep this file as draft: true so it never shows on the site.
Copy any block you need into your real post.
-->

## How to get the link

**Study chapter:**
1. Open the study on Lichess
2. Click the chapter you want
3. Copy the address from the browser bar — looks like:
   `https://lichess.org/study/WTvnkWAL/4Bv5ZXnA`
4. Works even when PGN download is turned off
5. Study must be **Public** or **Unlisted** (not Private)

**Single game:**
1. Open the game on Lichess
2. Copy the address — looks like:
   `https://lichess.org/q7ZvsdUF`

---

## Basic embed (no caption)

```
{{< lichess "https://lichess.org/study/WTvnkWAL/4Bv5ZXnA" >}}
```

{{< lichess "https://lichess.org/study/WTvnkWAL/4Bv5ZXnA" >}}

---

## Embed with a caption under the board

```
{{< lichess url="https://lichess.org/study/WTvnkWAL/4Bv5ZXnA" caption="Lucena position — rook behind the passed pawn" >}}
```

{{< lichess url="https://lichess.org/study/WTvnkWAL/4Bv5ZXnA" caption="Lucena position — rook behind the passed pawn" >}}

---

## Single game embed

```
{{< lichess "https://lichess.org/q7ZvsdUF" >}}
```

---

## Start the board at a specific move

Add `#20` (or any move number) to the end of the game link:

```
{{< lichess "https://lichess.org/q7ZvsdUF#20" >}}
```

{{< lichess "https://lichess.org/q7ZvsdUF#20" >}}

---

## Game with caption + starting move

```
{{< lichess url="https://lichess.org/q7ZvsdUF#20" caption="Black's mistake on move 20" >}}
```

---

## Quick-copy blanks

Paste these into your post and fill in the URL:

```
{{< lichess "PASTE-URL-HERE" >}}
```

```
{{< lichess url="PASTE-URL-HERE" caption="Your caption here" >}}
```

```
{{< lichess "PASTE-GAME-URL-HERE#MOVE-NUMBER" >}}
```

---

## Things to remember

| Situation | What to do |
|-----------|-----------|
| Study won't embed (blank board) | Check it's set to Public or Unlisted on Lichess |
| Want to show a specific position | Add #20 (or whatever move) to the game link |
| Board looks huge on desktop | Normal — it fills the column, max 760 px wide |
| Board on phone | Fits automatically, no extra steps |
| PGN download is off on the study | Still works — the embed only needs the link |
