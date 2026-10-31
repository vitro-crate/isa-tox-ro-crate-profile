# ISA-Tox RO-Crate Profile

An [RO-Crate](https://www.researchobject.org/ro-crate/) profile for *in vitro*
toxicology studies. It extends the
[ISA RO-Crate Profile](https://github.com/nfdi4plants/isa-ro-crate-profile)
with requirements on chemicals, test systems and the four
experimental step types, including SHACL shapes that check them.

| | |
| --- | --- |
| Specification | <https://vitro-crate.github.io/isa-tox-ro-crate-profile/1.0/> |
| Profile Crate | [`1.0/ro-crate-metadata.json`](1.0/ro-crate-metadata.json) |
| Permalink | `https://w3id.org/ro/crate/isa-tox/1.0` (not yet registered) |
| Version | 1.0.0 |

## Licence

Specification text [CC BY 4.0](LICENSE). The SHACL shapes live in [vitro-crate](https://github.com/johannehouweling/vitro-crate/tree/main/profiles/shapes/tox) under [MIT](https://github.com/johannehouweling/vitro-crate/blob/main/LICENSE).

## Contributing

This directory is generated. Source, issues and the reference implementation
live in [vitro-crate](https://github.com/johannehouweling/vitro-crate): the
specification is `profiles/docs/isa_tox.md`, the shapes are
`profiles/shapes/tox/`, and a release is one command —
`uv run python scripts/gen_profile_crate.py --out ../isa-tox-ro-crate-profile/1.0`.
