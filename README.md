# Hi, I'm Tost

I live in Piedmont, Italy. I write software for two things: studying with less friction, and getting more out of AI coding agents on the subscriptions I already pay for.

## cli-funnel

[cli-funnel](https://github.com/SuperTost100/cli-funnel) lets you call Claude Code, Codex, Cursor Agent and Antigravity like an API. Each CLI has its own flags, event format, login and model list. cli-funnel turns them into one call, one event stream and one result shape, and your runs count against the subscription you already have instead of an API bill. It also runs an OpenAI-compatible server, so any OpenAI SDK can use it, and ships React components for picking a model and signing in.

```bash
npm install cli-funnel
npx cli-funnel doctor
```

## Politost

Interactive textbooks and study tools for students.

- [Pyxis](https://github.com/SuperTost100/politost-pyxis): a desktop study tutor. Import your course material and an exam date, and it builds a plan with cited lessons, quizzes and flashcards. No account, no server.
- [Smartbook](https://github.com/SuperTost100/politost-smartbook): a web reader for smartbooks, textbooks with numbered formulas, worked exercises, a Python lab and graphs.
- [politost-content](https://github.com/SuperTost100/politost-content): the smartbook format. The spec, the parser and validator, and the CLI that packs a book into a `.ptsb` file.

## Tools

- [Smart Builder](https://github.com/SuperTost100/politost-smartbook-builder): turns lecture notes, textbooks and past exams into a smartbook, using the AI command-line tools you already pay for.
- [MoreOpenWhisperer](https://github.com/SuperTost100/moreopenwhispr): an OpenWhispr fork for desktop dictation with Antigravity, your own keys or local models, and no cloud account.
- [IWantAds](https://github.com/SuperTost100/IWantAds): a Zen Browser mod that switches your ad blockers off with one click, or on the sites you list.
