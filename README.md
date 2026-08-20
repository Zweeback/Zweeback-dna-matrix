# DNA Matrix

DNA Matrix is a bio-informatic encoding playground for mapping digital data into DNA-like symbol streams, evaluating storage characteristics and experimenting with error detection/correction strategies.

## Canonical direction

This repository succeeds the useful implementation work in `Aintropie/dna` and becomes the active Zweeback home for the project.

## Existing legacy engine concepts to recover

- UTF-8 / compressed payload handling
- DNA-symbol encoding and inverse decoding
- addressed oligos
- checksums / corruption detection
- erasure/parity experiments
- mutation and loss simulation
- GC-content and homopolymer metrics
- exact payload reconstruction
- visualization and export

## Target v0.8

1. Recover and test the strongest legacy encoder/decoder implementation.
2. Define one versioned binary/header format.
3. Add deterministic round-trip tests for Unicode, empty payloads and boundary sizes.
4. Add corruption/index/mutation/missing-oligo tests.
5. Replace weak XOR-only recovery with a documented FEC path (Reed–Solomon and/or fountain-code experiment).
6. Separate visualization from codec truth.
7. Preserve provenance of algorithms and scientific claims.

This is an experimental software/research project; it must not imply laboratory-grade DNA storage reliability without empirical validation.
