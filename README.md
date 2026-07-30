# perf-labs
Repository for temporary, experimental, performance-related static dashboards.

Live site: https://perf-labs.netlify.app/

## Running it locally

The dashboards are not in this repo. They live in their own repos, and
`netlify.toml` proxies them in, so the site only works if whatever serves it
reads that file. The Netlify CLI does:

```
npx netlify-cli dev
```

Then open http://localhost:8888.

No login or site linking needed. It pulls the real dashboards from wherever
they are already hosted, so what you see locally is what production serves.
