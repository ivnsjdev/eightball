# eightball

The public support and privacy site for **8 Ball**, served by GitHub Pages from `docs/`
on `main`.

```
https://ivnsjdev.github.io/eightball/            landing page
https://ivnsjdev.github.io/eightball/privacy/    privacy policy — App Store Connect, App Information
https://ivnsjdev.github.io/eightball/support/    support and FAQ — App Store Connect, version page
```

Every URL ends in a trailing slash, because `privacy/index.md` is served at `/privacy/`
and a request without the slash may 404. Both URLs are also compiled into the app, in
`Sources/Core/SupportContact.swift` of the app repo, where Guideline 5.1.1(i) requires the
policy to be reachable from inside it — so once a build ships carrying one, it must never
404 again.

This repo holds the site only; 8 Ball's source lives elsewhere. The same three pages are
still tracked in the app repo's own `docs/`, so a change made here must be mirrored there
until one of the two copies is retired.

The pages are written from the app's own source, never from a template: every sentence is
a claim about the binary. Re-verify them whenever 8 Ball gains an SDK, a permission, a
stored key, or a change in purchase terms — see the `app-store-pages` skill.
