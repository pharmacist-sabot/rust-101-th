# Rust-101 (Thai Edition)

```
██████╗ ██╗   ██╗ ██████╗████████╗██╗ ██████╗ ██╗
██╔══██╗██║   ██║██╔════╝╚══██╔══╝██║██╔═══██╗██║
██████╔╝██║   ██║███████╗   ██║   ██║██║   ██║██║
██╔══██╗██║   ██║╚════██║   ██║   ██║██║   ██║██║
██║  ██║╚██████╔╝██████╔╝   ██║   ██║╚██████╔╝██║
╚═╝  ╚═╝ ╚═════╝ ╚═════╝   ╚═╝╚═╝ ╚═════╝ ╚═╝
```

---

## ◆ PULSE

Rust has good English textbooks; what it lacks is a textbook in the
language a learner grew up with. This is a Thai translation and
adaptation of "Rust-101" by Ralf Jung - from fundamental concepts to
hands-on practice, built on mdBook so it reads as a web book with no
installation at all. Thai learners get a reference that speaks their
language, with credit to the original carried at every step and the
same license kept.

| Translated ▣ | mdBook ▣ | CC BY-SA ▣ | Free to read ▣ |
|---|---|---|---|

*The book - translate, adapt, publish - is built and open to
extension.*

> Translated and adapted from Rust-101 by Ralf Jung, released under
> CC BY-SA 4.0 like the original.
>
> **suradet-ps**, artifact keeper

---

## ◆ IGNITION

One install, one server.

```
⟫ cargo install mdbook
⟫ git clone https://github.com/suradet-ps/rust-101-th.git
⟫ cd rust-101-th
⟫ mdbook build
```

The book is generated in `./book` - open `index.html` directly, or
run `⟫ mdbook serve` and open
[http://localhost:3000](http://localhost:3000).

<details>
<summary>Prerequisites</summary>

- [Rust](https://rustup.rs/) with `cargo` (to install `mdbook`)
- A browser to read the book

</details>

---

## ◆ ANATOMY

One book, one original, a translation that keeps its credits.

- **Translates** - every chapter is translated and adapted from
  "Rust-101" by Ralf Jung - keeping technical terms precise while the
  explanations read naturally in Thai.
- **Adapts** - `src/` holds the chapters, `GLOSSARY.md` gathers the
  vocabulary, `theme/` shapes the mdBook look - the book is organized
  to read from fundamental concepts to practice.
- **Builds** - mdBook turns markdown into a web book with search,
  prev/next navigation, and print support - the familiar docs
  reading experience.
- **Credits** - the CC BY-SA 4.0 license is carried by both the
  original and the translation - every derivative must be shared
  under the same license, and the attribution is never dropped.

---

## ◆ RITUALS

**The core ceremony** - reading the first chapter:

1. Open the book - on GitHub Pages or through `mdbook serve` on your
   own machine.
2. Read the first chapter: Rust's fundamentals, explained in Thai.
3. Open the glossary when a term trips you - the vocabulary, complete
   in one page.
4. When you find a typo or a smoother phrasing, send a PR back - this
   edition grows with every helper.

**The ceremony of the credit** - this translation stands on the
original's shoulders: the author's name, the source link, and the
same license are written into the README wherever the work is
referenced - building on it means naming its roots.

**The ceremony of mdBook** - a textbook about code should be built
with a developer's tool: one build, one `book/` folder, and a book
that opens on any machine.

---

## ◆ ECHOES

**Where this book is heading**

```
translate ▸ chapters translated and adapted from the original ──────── ▸ sealed
build     ▸ mdBook: build + serve ──────────────────────────────────── ▸ sealed
publish   ▸ GitHub Pages with a deploy workflow ─────────────────────── ▸ sealed
extend    ▸ glossary and new chapters - open to contribution ────────── ▸ open
```

**Raising the artifact** - fork, branch, fix the wording or improve
the phrasing, and open a pull request - every edit helps Thai
learners everywhere. Open an issue first to discuss larger changes.

**Status** - CI checks every push and deploys the book to GitHub
Pages automatically. [Watch the workflow](.github/workflows).

---

```
  ─────────────────────────────────────────
   A textbook in the language you grew up in
   is a textbook you finish.
  ─────────────────────────────────────────
```

Released under [CC BY-SA 4.0](LICENSE), like the original.