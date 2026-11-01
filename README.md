# Test The Internet

A transparent browser connection diagnostics page. It reports browser online status and optional Network Information API estimates, then attempts three tiny third-party connectivity requests. Copy a diagnostic summary.

## Features

A transparent browser connection diagnostics page. It reports browser online status and optional Network Information API estimates, then attempts three tiny third-party connectivity requests. Copy a diagnostic summary.

## How to use

1. Open `index.html` in a modern browser.
2. Follow the instructions on the page.
3. Your data stays local unless you deliberately copy or export it. The internet tester makes requests to its named external endpoints.

## Deploy to Vercel

Import this GitHub repository. Choose **Other** as the framework, root directory `./`, leave output directory unset, and turn **off** any Build Command override. There is no Node build step.

## Limitations

Opaque fetch requests cannot prove valid HTTP responses, and timings are not ICMP ping, packet loss, or throughput measurements.

## Tech stack

Plain HTML, CSS, and JavaScript with no installation requirements.

## License

MIT. Built by [Ikram Salhi](https://github.com/ikramsalhi).
