# 🧊 Iceopt

> ⚠️ **Project is under active development and not yet usable. This repo is currently a skeleton and does not perform any real Iceberg operations.**  
> Stay tuned — `iceopt` will soon become a powerful CLI for optimizing Iceberg tables.

---

## 🔍 What is Iceopt?

**Iceopt** is a Rust-based CLI tool for **analyzing and optimizing Apache Iceberg tables**. It’s designed to help data engineers, platform teams, and lakehouse maintainers:

- Identify small files, skewed partitions, and layout inefficiencies
- Suggest optimal partitioning and sort strategies
- Compact fragmented data and rewrite manifests
- Improve query performance and reduce storage costs
- Integrate into CI/CD workflows or scheduled jobs for data lake hygiene

---

## 🚧 Status

| Feature | Status |
|--------|--------|
| CLI Scaffolding | ✅ Done |
| Analyze Command | 🛠️ Planned |
| Compaction Engine | ⏳ Not started |
| Layout Suggestion Engine | ⏳ Not started |
| Reporting System | ⏳ Not started |

---

## ✨ Planned Features

- `iceopt analyze` – Audit table layout and health
- `iceopt lint` – Show warnings for inefficient table design
- `iceopt compact` – Merge small files intelligently
- `iceopt suggest` – Propose improved partitioning or sort strategies
- `iceopt apply` – Execute optimization plans
- JSON/Markdown reporting
- Dry run mode (`--simulate`)
- Object store + local path support

---

## 💡 Why Iceopt?

Modern data lakes built on Apache Iceberg need more than just ingestion and queries — they need **continuous optimization** to stay efficient at scale. Iceopt will be the companion tool for keeping your tables healthy, performant, and clean.

---

## 📦 Tech Stack

- Language: **Rust**
- Iceberg I/O: [`apache/iceberg-rust`](https://github.com/apache/iceberg-rust) *(planned)*
- CLI Framework: [`clap`](https://docs.rs/clap)
- Object Storage: `object_store`, `aws-sdk-s3` *(planned)*
- Reporting: `serde_json`, `indicatif`, `plotters` *(planned)*

---

## 🛠️ Getting Started

> This project is not ready for use yet.  
> If you're curious or want to contribute early, clone the repo and follow along as we build.

```bash
git clone https://github.com/your-org/iceopt.git
cd iceopt
cargo run
```

---

## 📅 Roadmap

- [ ] CLI skeleton
- [ ] Table analysis module
- [ ] Compaction logic
- [ ] Lint rules engine
- [ ] Report formatting (JSON, Markdown)
- [ ] CI test suite
- [ ] Documentation

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ✉️ Contact

Made with ☕ by [Mathew Bravo](mailto:mathew@Mathew).

Feel free to open an issue or submit a PR if you'd like to get involved early.

