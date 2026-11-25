# workshop-oauth

Static OAuth redirect "bounce" pages for the Workshop desktop app (Slack requires HTTPS redirect URLs).
`slack-callback.html` forwards only `code`, `state` and `error` to `http://localhost:8787/api/oauth/slack/callback` (port overridable with `#port=NNNN`). No backend, no storage, no external scripts.
