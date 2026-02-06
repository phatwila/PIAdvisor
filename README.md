# PIAdvisor PixInsight Update Repository

This repository is the PixInsight update feed for **PIAdvisor**. It hosts:

- `updates.xri` (the PixInsight repository manifest)
- `packages/*.zip` (update archives containing `bin/*` + `doc/*`) when public packages are available

## Repository URL

Add the GitHub Pages URL for this repo in PixInsight:

```text
https://phatwila.github.io/PIAdvisor-Release/
```

Tip: PixInsight is sensitive to redirects. Use the exact URL that serves `updates.xri` directly.

## Status

No public packages are published yet (awaiting CPD approval). You can still browse the documentation at:

```text
https://phatwila.github.io/PIAdvisor-Release/docs/
```

## Install in PixInsight

1) Resources → Updates → Manage repositories → Add repo URL (must serve `updates.xri`)
2) Resources → Updates → Check for Updates
3) Apply updates, restart PixInsight
