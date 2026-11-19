# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `landing-waitlist`

Writes a landing page and waitlist for a new product: headline, benefits, call to action, a minimal sign-up form, a plain-language privacy notice, tracked links and the welcome message, with a ready-to-publish HTML page on request.

**How it works**

1. **Ask first.** What it does, who it's for, the one action you want, and who reads the sign-ups.
2. **Page copy** with two headlines to test.
3. **The form**: the fewest fields that work.
4. **Privacy notice** in plain words, with a delete-by date and an adult contact for teen founders.
5. **Tracked links**, one per channel, and the **welcome message**.
6. **A pre-launch checklist**, and a single-file HTML page when you ask for one.

It collects the minimum and never asks for a minor's personal details beyond what the product needs.

It is one stage of [gtm-pipeline](https://github.com/BuiltYoung/gtm-pipeline), the GTM super agent, and also works on its own.

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/landing-waitlist.git ~/.claude/skills/landing-waitlist
```

Restart Claude Code. The skill loads automatically when your request matches it.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `landing-waitlist` folder.

---

## Using it

Describe what you need. No command needed:

> *"Make us a waitlist page for our study app. We'll share it on Instagram and at school."*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. See [LICENSE](LICENSE). Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
