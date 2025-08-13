# 🌐 scrapurl

A simple and colorful Rust command-line tool to scrape all links from a webpage.  
Built with [Actix-inspired async Rust](https://tokio.rs/), [`reqwest`](https://docs.rs/reqwest/), and [`scraper`](https://docs.rs/scraper/).

---

## ✨ Features
- Fetches any webpage and extracts all `<a href="...">` links
- Colorful and user-friendly CLI output
- Built for speed using async Rust (`tokio`)
- Displays total link count
- Your personal branding 🖤

---

## 📦 Installation
Clone the repo and build:
```bash
git clone https://github.com/anomalous254/scrapurl.git
cd scrapurl
cargo build --release
```

## Uasge
```bash
cargo run -- <URL>
```

#### Example
```bash
cargo run -- https://exampe.com
```


## 🛠 Dependencies

`reqwest` — HTTP client

`scraper` — HTML parsing

`tokio` — Async runtime

`colored` — Terminal colors
