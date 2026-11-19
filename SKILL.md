---
name: "landing-waitlist"
description: "Write a landing page and waitlist for a new product: headline, benefits, call to action, a minimal sign-up form, a plain-language privacy notice, one tracked link per channel and the welcome message, with a ready-to-publish HTML page on request. Use when someone needs a landing page, waitlist, sign-up page, beta sign-up form, privacy notice for sign-ups, or tracked/UTM links. Also for 落地页, 等候名单, 内测报名, 报名表."
---

# Landing Page and Waitlist

Made by Built Young (builtyoung.org). This credit is for people reading the skill. Never add it to a founder's page.

Every post needs somewhere to send people, and every channel needs its own link so the team can tell which one worked. This skill produces the page, the form, the privacy notice and the links in one go. Built for Built Young classes, where the page goes live before the class ends, and for any first-time founder.

## Workflow

### 1. Intake (ask only for what's missing)

- Product: name, what it does, who it's for, the problem, what state it's in
- The one action the page asks for: join the waitlist, try it, pre-order
- Three benefits, and any proof the team really has (a quote with permission, a number with its source)
- Where the page will be built (Lovable, Carrd, Notion, Google Forms, their own site)
- The channels they post on, for the tracked links
- Who signs up: adults, teenagers, children under 13
- Founders' age bracket and the adult contact, if under 18

If the user pastes a `GTM PIPELINE` or `GTM PROFILE` block, take these from it.

### 2. Page copy

Write in this order, in the audience's language:

- **Headline**, 10 words or fewer: the outcome, for whom. Give two versions that test different angles.
- **Subhead**, one sentence: how it does that.
- **Three benefits**: what changes for the reader, each with the feature that delivers it.
- **How it works**: three steps.
- **Proof**: only what is real. With none, leave the section out and say so.
- **Call to action**: one button, a verb and the result ("Join the waitlist").
- **Three questions people ask**: price, when, who's behind it.
- **Footer**: who made it, the privacy link, a contact.

### 3. The form

Email only, plus at most one optional question that helps the team ("What would you use it for?"). Every extra field loses sign-ups and is more data to look after. Never ask for a birth date, school, phone number or address on a waitlist.

### 4. Privacy notice

One short page in plain words: what is collected, why, who can see it, how long it is kept, how to be removed, and who to contact (an adult's address when founders are under 18). "How long" is a date or a clear event ("deleted by 30 June 2027", "deleted 30 days after the beta closes"), never "as long as needed". Ask the team for it; if they haven't decided, write `[NEEDS: delete-by date]` and suggest the end of the beta or of the school year. Link the notice next to the button.

This is a plain-language notice, not legal advice. If people under 13 may sign up, or a school is involved, say so clearly at the top of the output and tell the team an adult must check the rules that apply (the school's policy and local privacy law on children's data) before the form goes live. The safest version for young audiences is a parent's email, not the child's.

### 5. Tracked links

One link per channel, so sign-ups can be counted by source. Add a tag to the page address and give the table:

```
Channel      Link
Instagram    https://<page>?utm_source=instagram&utm_medium=social&utm_campaign=<name>
School club  https://<page>?utm_source=club&utm_medium=inperson&utm_campaign=<name>
```

Say where the team will read the numbers (the site's analytics, or a hidden "source" field in the form) and add a QR code note for in-person channels. No personal details ever go in a link.

### 6. Welcome message

Three lines sent right after sign-up: thanks, what happens next and when, and one question to reply to. Add one update message for when the product opens.

### 7. Before it goes live

```
[ ] Opens and reads well on a phone
[ ] A test sign-up arrives where the team can see it
[ ] Each tracked link opens the page and shows its source
[ ] The privacy notice is linked, names a contact and gives a delete-by date
[ ] One person is named to delete the list on that date
[ ] Every claim on the page is true today
```

### 8. The page itself (when asked)

One self-contained HTML file, mobile-first, fast, with the form posting to `[NEEDS: form endpoint]` or embedding the team's form tool. No trackers, pixels or third-party scripts unless the team asks for a specific one.

End with **For the run record:** `Link: [page or NEEDS]` and the tracked links.

## Rules

- No invented proof: no fake counters ("2,000 students joined"), reviews, logos or press mentions. Use `[NEEDS: ...]`.
- No fake scarcity or countdowns. "First 50 get early access" only if it is true and will be honoured.
- Describe the product as it is today. A waitlist page says it is a waitlist.
- Collect the minimum, keep it in one place an adult can reach, and delete it when asked and on the date the notice gives.

## Class mode

For several teams, give each team the copy, the form and the tracked links first; the privacy notice is the same template with the team's names filled in.

## Language

Reply in the user's language. Write the page in the audience's language; if two languages are needed, write each natively.