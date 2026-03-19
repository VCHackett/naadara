# Contributing to Naadara

First — thank you. Naadara is built on the idea that frequency knowledge belongs to everyone. Every contribution, no matter how small, helps make that real.

---

## Ways to Contribute

You don't need to write code to contribute. Here's what's valuable:

### 🎵 Frequency Knowledge
The 23-category library is a living document. If you know of frequencies that should be added, corrected, or better labelled — open an Issue or a Discussion. Researchers, sound healers, musicians, and domain experts are especially welcome.

### 🐛 Bug Reports
Found something broken? Open an [Issue](https://github.com/VCHackett/naadara/issues) and describe:
- What you were doing
- What happened
- What you expected
- Your browser and OS

### 💡 Feature Ideas
Have an idea for a new display mode, frequency category, export format, or UI improvement? Start a [Discussion](https://github.com/VCHackett/naadara/discussions) under **Ideas**. Big ideas are welcome. Wild ideas are especially welcome.

### 🔧 Code Contributions
Bug fixes, performance improvements, new features — all welcome via Pull Request.

### 📖 Documentation
Found something in the Instructions module that's wrong or missing? Spot a typo? Submit a fix.

---

## Getting Started with Code

Naadara is a single HTML file — there's no build step, no package manager, no framework.

```bash
git clone https://github.com/VCHackett/naadara.git
cd naadara
open index.html
```

That's it. Edit `index.html`, refresh your browser, see the change.

For features requiring microphone or recording (which need a secure context):

```bash
python3 -m http.server 8080
# Open http://localhost:8080
```

---

## Submitting a Pull Request

1. **Fork** the repo — click Fork on GitHub
2. **Clone** your fork locally
3. **Create a branch** — name it something descriptive like `add-runic-frequencies` or `fix-binaural-sweep`
4. **Make your changes** in `index.html`
5. **Test it** — open in Chrome and Firefox, check the feature you changed works, check you haven't broken anything obvious
6. **Commit** with a clear message: `Add 9 Futhorc runic frequencies to Norse category`
7. **Push** to your fork
8. **Open a Pull Request** — describe what you changed and why

PRs don't need to be perfect. If you're unsure about something, open it as a Draft PR and ask.

---

## Guidelines

- **Don't break existing features.** Test your change before submitting.
- **One thing per PR.** Smaller PRs are easier to review and faster to merge.
- **Document frequency sources.** If adding frequencies, include a reference or explanation in your PR description.
- **Keep the single-file architecture.** Naadara is intentionally one HTML file — no external scripts, no npm, no build tools.
- **Be kind.** This is a community project. Assume good intent.

---

## Frequency Contribution Format

When suggesting new frequencies, this format helps:

```
Category: [which of the 23 categories, or suggest a new one]
Hz: [frequency in Hz]
Name: [display name — keep it short, max ~25 chars]
Source: [where this comes from — research paper, cultural tradition, calculation method, etc.]
```

Example:
```
Category: Bioacoustic & Nature
Hz: 18.98
Name: Tiger infrasound
Source: Research on tiger communication — tigers use 18 Hz infrasound to stun/disorient prey
```

---

## Community

- **GitHub Discussions** — main forum for ideas, questions, research sharing
- **GitHub Issues** — bug reports and specific feature requests

---

## Licence

By contributing to Naadara, you agree that your contributions will be licensed under the **MIT Licence** that covers this project. Your name will be credited in the Contributors section.

---

*Naadara is free, forever. Thank you for helping keep it that way.*
