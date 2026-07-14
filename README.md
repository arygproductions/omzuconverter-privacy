# Privacy Policy — OmzuConverter

**Last updated: 14 July 2026**

OmzuConverter is published by ARYG Productions ("we"). It exists so that you can work
with your documents without handing them to anyone — including us.

This policy covers the **OmzuConverter mobile app** (iOS and Android) and the
**OmzuConverter desktop / self-hosted server** (macOS, Windows, Docker).

---

## The short version

**We do not collect, transmit, store, sell, or share any of your data.** There is no
account, no sign-in, no analytics, no advertising, no tracking, and no crash reporting.
Your files are processed on your own device and never sent to us.

---

## The mobile app

Every one of the app's 24 tools runs entirely **on your device**. When you merge, split,
compress, OCR, protect, sign, or convert a document, the work is done locally by code
inside the app. The file never leaves your phone.

- **We receive nothing.** OmzuConverter has no server of ours to talk to. There is no
  endpoint that your documents could be uploaded to.
- **No account, no identifiers.** We do not ask for your name, email, phone number, or
  any device or advertising identifier.
- **No analytics or ads.** The app contains no analytics SDK, no advertising SDK, and no
  third-party tracking library.
- **Files you open** are the ones you explicitly pick, and results are written only where
  you choose to save or share them.
- **App storage.** The app remembers a small amount of local preference data (for example,
  whether you chose the light or dark theme). This stays on the device and is not
  readable by us.

The Android build declares the `INTERNET` permission because it is part of the default
app framework the project is built on; the app makes no network requests.

## The desktop app and the self-hosted server

The desktop app runs a small web server **on your own machine** and serves the interface
to your own browser. Your documents stay on that machine. We operate no service and
receive no data from it.

Two features are **optional and off unless you configure them**: the AI Summarizer and
the Translate tool. They are "bring your own LLM" — they do nothing until *you* supply
the address of a language-model endpoint (which may be one running locally, such as
Ollama or LM Studio, or a third-party service such as OpenAI). If, and only if, you
configure a third-party endpoint and then use one of those two tools, the text you
submit is sent to **that provider you chose**, and their privacy policy governs it. We
are not a party to that. No other tool contacts the network, and these two tools are not
present in the mobile app at all.

If you make your self-hosted server reachable on your local network, access is protected
by a token; you are responsible for who you share that link with.

## Children

OmzuConverter is a general-purpose document utility. It is not directed at children and
collects no data from anyone, including children.

## Legal requests

We hold no user data, so there is nothing for us to disclose, produce, or hand over — to
anyone, for any reason.

## Your rights

Rights such as access, correction, deletion, and portability apply to data a company
holds about you. We hold none. Deleting the app removes everything it kept on your
device.

## Open source

OmzuConverter is free software licensed under the **GNU AGPL-3.0-or-later**. If you have
received a copy of the app, you are entitled to its complete corresponding source code —
email **yezdi.ghadially@gmail.com** and we will provide it. So these claims are not
something you have to take on trust: you can read the code and verify for yourself that
no data leaves your device.

## Changes to this policy

If this policy ever changes, the updated version will be posted at this URL with a new
"last updated" date.

## Contact

Questions about this policy: **yezdi.ghadially@gmail.com**
