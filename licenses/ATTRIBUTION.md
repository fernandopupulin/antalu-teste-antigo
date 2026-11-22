# Project origin and credits

The Antalos selector derives from **nap-time**, the Blast Radius entry referred to here as “teste antigo”, by Jason Scheffel. Antalos adapted the selector and its TPC-DS verification. [Upstream repository](https://github.com/jason-scheffel/nap-time)

The upstream MIT license and copyright notice are in [LICENSE](LICENSE). The author requested that other teams avoid reusing the entry during the event. [Original notice](NOTICE.md)

## Competition starter kit

The sample patches, test manifest, sample answers, scoring script, Makefile and scoring documentation come from the RWX Blast Radius starter kit. [Track and starter kit](https://www.joinbuilders.org/buildathon/tracks/blast-radius)

## Build sources

The Docker build uses the pinned SQLGlot source tree and a CPython distribution from Astral's python-build-standalone project. The build reads the URL templates in [base-tree.url](base-tree.url) and [interpreter.url](interpreter.url).

## Use of AI

Antalos used OpenAI Codex to analyze selector performance, implement changes to TPC-DS query sampling, and validate those changes against labeled patches.
