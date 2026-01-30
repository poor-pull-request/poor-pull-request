# $PPR — Poor Pull Request 🚩

> *For pull requests that change one character and still require approval.*

$PPR is a community-driven, developer-native meme project dedicated to celebrating the most unnecessary, ceremonial, and emotionally taxing pull requests in modern software development.

If you’ve ever opened (or reviewed) a PR that:

* adds a single `.`
* fixes a typo
* removes trailing whitespace
* technically required CI, reviews, and a meeting

…this project is for you.

---

## What is this?

This repository exists to:

* Archive and celebrate **Poor Pull Requests**
* Automatically detect microscopic PRs
* Apply appropriate social consequences (labels, comments, LGTM)
* Serve as the canonical home of the $PPR meme

This is **not** a serious financial project.
This **is** a serious cultural one.

---

## Features

### 🚦 Tiered PR Behavior (Automated)

Using GitHub Actions, PRs are evaluated and handled according to their *emotional weight*:

| Change Size    | Outcome                                                    |
| -------------- | ---------------------------------------------------------- |
| 0 changes      | 🧘 Comment: *"No changes detected. Incredible restraint."* |
| 1 character    | ✅ Auto LGTM + `ceremonial-pr` label                        |
| 2–5 characters | 🚩 `poor-pull-request` label + warning comment             |
| >5 characters  | 😐 Treated as a real PR                                    |

---

## Labels

### 🚩 `poor-pull-request`

> This could have been a commit

Applied to PRs that introduce minimal changes but still demand disproportionate process.

### 👑 `ceremonial-pr`

> One character. Full ceremony.

Reserved for the most elite PRs imaginable.

---

## The Philosophy

We believe:

* Not every change needs a pull request
* But if it *does* become a pull request, it should at least be funny
* Process without proportion is comedy
* CI/CD should suffer, just a little

---

## How to Contribute

We welcome contributions, especially:

* Extremely small PRs
* Bad ideas executed perfectly
* Documentation changes no one asked for

Please read [`CONTRIBUTING.md`](./CONTRIBUTING.md) before opening a PR.

> **Note:** PRs under 5 characters may be labeled automatically.
> PRs under 1 character may be approved instantly.

---

## Pull Request Template

This repository uses a **mandatory pull request template** designed to ensure that every change—no matter how small—receives the level of ceremony it deserves.

The template will prompt you to:

- Explain why your change required a pull request
- Declare the emotional impact of your diff
- Admit whether this could have been a commit

If your PR feels excessively reviewed for its size, the system is working as intended.

You can preview the template here:

- [`.github/pull_request_template.md`](./.github/pull_request_template.md)


---

## Frequently Asked Questions

### Is this a real token?

Yes.

### Is this a serious project?

No.

### Why does this exist?

Because it keeps happening.

### Can I use this GitHub Action in my own repo?

Absolutely. Please do. Spread the culture.

---

## Disclaimer

This repository is satire.

Any resemblance to real pull requests, living or dead, is entirely intentional.

---

## Final Notes

If this README made you uncomfortable, you may have reviewed one of these PRs recently.

LGTM 👍.
