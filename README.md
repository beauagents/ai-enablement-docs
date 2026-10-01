# AI Enablement Documentation

A provider-neutral documentation set for an AI enablement system: layers, contracts, governance, memory, credentials, execution, visibility, resilience and cost control, described with generic capability names.

This repository contains documents only. It has no application code, deployment instructions, credentials or named-provider architecture on the main branch.

**Status:** scaffold v0.1.0. Structure, requirements, seed sources and 22 research workstreams are in place. The workstreams will be completed as separate commits.

## Two views of one body of content

| View | Location | For |
|---|---|---|
| Human vault | `vault/` | The Human principal and human collaborators. Obsidian-compatible, with wikilinks and reading paths. |
| AI corpus | `ai-corpus/` | Agents. Small chunks projected from the vault, with metadata for role filtering and source identifiers. |

The vault is authoritative. Chunks reproduce vault sections unchanged and record a hash of the parent section so divergence can be detected.

Open the repository root as an Obsidian vault. Wikilinks use shortest-path note names, so note file names are unique across the repository.

## Evidence chain

```
claim -> wikilink -> parsed source record -> archive manifest -> original or versioned location
```

- `sources/records/`: parsed source records.
- `sources/archive/`: archive manifests.
- `sources/Source-Registry.md`: the registry.

At scaffold, every record is summary-extracted and every manifest says not-captured. Full parsing and capture are workstream tasks.

## Layout

```
README.md, CONTRIBUTING.md, llms.txt
vault/        human vault (foundations, governance, behavior, architecture, visibility, resource governance, research output, citations, workstreams, reading paths, glossary, meta-templates)
ai-corpus/    chunk schema, retrieval rules, chunk index, chunks
sources/      source registry, records, archive manifests
registers/    requirements, decisions, open questions
.github/      pull request and research issue templates
```

Start at [vault/00-Home.md](vault/00-Home.md).

## Rules that apply to every change

- Neutral language on main. Provider names appear only as evidence inside source records.
- Researchers present all credible options with documentation links. They do not make architectural decisions.
- Every substantive claim carries a label (FACT, INFERENCE, RECOMMENDATION, UNRESOLVED, USER DECISION, USER REQUIREMENT, UNVERIFIED).
- No personal or diagnostic labels about the Human principal.
- Approved material changes by signed supersession, not by editing in place.
