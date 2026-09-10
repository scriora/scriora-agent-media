# Contributing to Scriora agent media

This repository is **media transforms and skills**, not the social publisher.  
Product policy: [scriora-core CONTRIBUTING](https://github.com/scriora/scriora-core/blob/main/CONTRIBUTING.md).  
Sign the [CLA](CLA.md) once. License: [Apache-2.0](LICENSE).

## We accept

- Streaming transforms with golden fixtures
- Skill manifests that validate against the schema
- Memory-bound tests (do not load the whole file as the happy path)
- Codec / FFmpeg probe improvements

## We reject (even if CI is green)

- “Just buffer the whole video in RAM”
- Skills that call unofficial social publish APIs
- Secrets in fixtures or manifests
- Copying core RLS / Compose CI into this repo
- Unreviewed AI dumps

## Sending a pull request

Fork, one concern, wait for **this repo’s** checks (`FFmpeg`, `Fixtures`, `Skill manifest`, `CLA`, `Secret scan`).

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and [SECURITY.md](SECURITY.md).
