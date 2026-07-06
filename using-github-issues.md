# Communicating via GitHub Issues

*An informal guide for participants of this Community Group.*

> This guide explains how we use **GitHub Issues** to discuss topics in the open. No deep technical background is assumed.

---

## 1. Why GitHub Issues?

A Community Group (CG) can talk over the mailing list, on live calls, or on GitHub. GitHub Issues have some particular strengths:

- **Asynchronous** — write when it suits you, across time zones. You can take part even if you can't join live calls.
- **Public and archived** — the discussion stays readable by anyone, later. This fits W3C's "public by default" principle.
- **Organized by topic** — one topic = one issue. Threads don't get buried the way email can.
- **Decisions you can point to** — you can show exactly where and why something was discussed or decided.

In short: **an open, searchable, well-organized place to deliberate.**

---

## 2. Map of the repository

A CG repository (e.g. `w3c-cg/embedded-web-engines`) has a few "rooms":

| Room | What it's for |
|---|---|
| **Issues** | Raise one topic, question, proposal, or problem at a time, and discuss it. **The focus of this guide.** |
| **Discussions** | Looser, open-ended Q&A / brainstorming (if enabled). |
| **Pull Requests (PRs)** | Concrete **changes to documents** (draft text, README) that are reviewed and merged. |
| **README / CONTRIBUTING** | The front-door documents: what the group is, and how to take part. |
| **CODE_OF_CONDUCT** | The code of conduct (W3C CEPC) — how we keep participation welcoming. |

> Rule of thumb: **to talk, open an Issue; to change a document, open a PR.**

---

## 3. Opening an issue

1. Go to the **Issues tab → "New issue."**
2. **Title**: a specific, searchable sentence.
   - Good: *"Terminology: distinguishing `embedded runtime` from `native runtime`"*
   - Avoid: *"Question," "bug"*
3. **Body**: three things help a lot.
   - **Background / motivation** (why raise this)
   - **The point / proposal** (what you want to decide or suggest)
   - **Links** (related specs, issues, resources)
4. "Submit new issue."

> Tip: **one topic per issue.** If it grows, split it into separate issues. And **search existing issues first** to avoid duplicates.

---

## 4. Commenting and reacting

- Write comments in **Markdown** (headings, lists, code, quotes — see appendix).
- To signal agreement or "I've read this," use an **emoji reaction (👍)** instead of adding a comment. It keeps the thread clean.
- **Quote** the person or comment you're replying to, so the flow is clear.
- Be considerate and welcoming to everyone, including newcomers (that's the **CEPC**, our code of conduct).

---

## 5. Linking issues and people

- `#123` links to **issue/PR #123**; `owner/repo#123` references another repository.
- `@username` **mentions** someone (they get notified). Use it to pull in a specific person.
- Writing `Fixes #123` in a commit or PR **auto-closes that issue** when it is merged.

---

## 6. Notifications (so you don't miss things)

- Use **"Watch"** (top-right of the repo) to choose your notification level:
  - **Participating and @mentions** — only threads you're involved in. **Recommended** (not too noisy).
  - **All Activity** — everything (can be a lot on an active repo).
- Use **"Subscribe"** on an individual issue to follow just that topic.

---

## 7. Which channel? Issues vs Discussions vs PRs vs mailing list

| Channel | Best for |
|---|---|
| **Issue** | Discussion of a specific topic (one point per issue) |
| **Discussions** | Open-ended **brainstorming / Q&A** with no urgent conclusion (if enabled) |
| **Pull Request** | **Concrete document changes** (review the diff, then merge) |
| **Mailing list** | **Announcements**, reaching people who don't watch GitHub, the formal record |

> A common flow is **"announce on the list → discuss in an Issue → reflect via a PR."**

---

## 8. A few W3C-specific notes

- **Public by default** — issues, PRs, and the archive are public.
- **CLA (Community Contributor License Agreement)** — if you make a **substantive contribution** to spec text, you'll need to have agreed to the W3C CLA. A bot checks this on PRs and will let you know if you haven't.
- **CEPC (Code of Ethics and Professional Conduct)** — everyone follows it; be respectful and inclusive.
- **CG output is not a Recommendation** — CG reports are useful, but they are **not an official W3C standard.** Please word things accordingly.

---

## 9. Checklist — how to write a good issue

- [ ] A **specific, searchable** title
- [ ] **One issue = one topic**
- [ ] Include background, the proposal, and links
- [ ] **Search** existing issues first (avoid duplicates)
- [ ] React with **emoji**; discuss in **comments**

---

## Appendix — handy tricks & glossary

### Markdown quick reference

```
**bold**  *italic*  `code`
- bullet list
> blockquote
[link text](URL)
​```code block​```
```

### Linking

- `#123` — link to an issue/PR; `owner/repo#123` — reference another repository
- `@username` — mention (sends a notification)
- `Fixes #123` in a commit/PR — auto-closes that issue when merged

### Glossary

- **Issue**: a post to discuss one topic — **PR**: a proposed document change
- **consensus**: reaching agreement by resolving objections (not a majority vote)
- **CEPC**: W3C Code of Ethics and Professional Conduct — **CLA**: Contributor License Agreement

---

*This is an informal guide to general practice. For this group's formal rules, follow the repository's README / CONTRIBUTING and the W3C Community and Business Group Process.*
