# Sumanta Kabiraj

I build self-hosted developer tools in Go — things that ship as one static binary,
keep their data in SQLite, and run on a box you own rather than someone else's.

[sumanta.ai](https://sumanta.ai)

## Mailora

Four email tools under [github.com/mailora](https://github.com/mailora). Each is a single Go binary
with a React UI embedded in it, `CGO_ENABLED=0`, SQLite, MIT.

- **[Send](https://github.com/mailora/send)** — email sending platform. Resend-style `/v1` API,
  templates, audiences, broadcasts, DKIM, webhooks, SMTP relay. → [send.mailora.app](https://send.mailora.app)
- **[Trap](https://github.com/mailora/trap)** — development mail catcher. Captures everything your
  app sends and delivers nothing. SMTP, POP3, IMAP. → [trap.mailora.app](https://trap.mailora.app)
- **[Temp](https://github.com/mailora/temp)** — disposable email. TTL-scoped inboxes, live push,
  DKIM-signed replies. → [temp.mailora.app](https://temp.mailora.app)
- **[Mail](https://github.com/mailora/mail)** — full mail server. Inbound SMTP, IMAP, outbound queue
  with DKIM, automatic TLS, webmail. → [mail.mailora.app](https://mail.mailora.app)

## Other public work

- **[ccslot](https://github.com/sumantadotai/ccslot)** — run multiple Claude Code accounts on one
  machine, with separate logins but shared projects, skills, plans and settings.
- **[CourseSupportBot](https://github.com/sumantadotai/CourseSupportBot)** — RAG support bot over
  course subtitles. Go single binary, SQLite, OpenAI.
- **[tiaopen-mcp](https://github.com/sumantadotai/tiaopen-mcp)** — MCP server exposing the Siemens
  TIA Portal Openness API, so an agent can create, write and compile PLC blocks.

Most of what I work on is still private. It surfaces here when it is worth someone else's time.

## How I work

Go 1.26 and the standard library, React 19 for anything with a UI, SQLite until it genuinely stops
being enough. No framework where `http.ServeMux` does the job, no dependency where a few lines do.

Reachable at [sumantablog@gmail.com](mailto:sumantablog@gmail.com).
