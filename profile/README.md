<div align="center">

**The flexible crawler and scraper framework for Rust.**

Crawl websites over HTTP or in real browsers, route every page to a typed
handler, and extract structured data, built on tokio.

[**The Spire Book**](https://spire-rs.github.io/spire) · [**docs.rs/spire**](https://docs.rs/spire) · [**crates.io/crates/spire**](https://crates.io/crates/spire) · [**github.com/spire-rs/spire**](https://github.com/spire-rs/spire)

</div>

## Crates

| Crate | Version | What it does |
| --- | --- | --- |
| [spire](https://github.com/spire-rs/spire) | [![spire](https://img.shields.io/crates/v/spire.svg?style=flat-square)](https://crates.io/crates/spire) | The crawler and scraper framework: frontiers, HTTP and browser backends, typed routing and extractors. |
| [robotxt](https://github.com/spire-rs/kit/tree/main/robotxt) | [![robotxt](https://img.shields.io/crates/v/robotxt.svg?style=flat-square)](https://crates.io/crates/robotxt) | Parses and builds robots.txt files following RFC 9309, with the `crawl-delay` and `sitemap` extensions. |
| [sitemapo](https://github.com/spire-rs/kit/tree/main/sitemapo) | [![sitemapo](https://img.shields.io/crates/v/sitemapo.svg?style=flat-square)](https://crates.io/crates/sitemapo) | Parses and builds text and XML sitemaps and sitemap indexes, with the image, video, news and `hreflang` extensions. |
| [countio](https://github.com/spire-rs/countio) | [![countio](https://img.shields.io/crates/v/countio.svg?style=flat-square)](https://crates.io/crates/countio) | Byte counting for readers and writers, for `std::io`, tokio and futures. |

## Getting started

[The Spire Book](https://spire-rs.github.io/spire) is the guide: handling pages, discovering
them, fetching over HTTP or with a browser, running and resuming a crawl, and extending spire.
The API reference lives on [docs.rs](https://docs.rs/spire).
