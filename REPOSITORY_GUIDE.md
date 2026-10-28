# Repository Purpose and Maintenance Rules

## Identity and scope

**This is a README-first publication and DOI library for Joe Nasr (Joseph Ribal Nasr). It is NOT a website development project.**

The primary user-facing deliverable is the GitHub repository's `README.md`, which lists research publications, books, DOIs, publication-record URLs, related project/repository URLs when documented, and researcher-profile links.

The repository may contain legacy HTML research notes and supporting files. Their presence does **not** authorize creating, redesigning, deploying, or promoting a website. Do not refer to GitHub Pages as the main library or offer a “preview” URL for the README. The correct library URL is the GitHub repository itself.

## What to do when maintaining this repository

1. **Read this file first**, then `README.md`, `registry.json`, and any relevant publication source before editing.
2. Treat `README.md` as the **primary human-readable publication library**. Keep a single clear table with the **exact publication title**, **type** (only if verified), **DOI link**, **publication website/record link**, and **related source or project URL** if one is established. Avoid redundant lists and lengthy unsupported descriptions.
3. Treat `registry.json` as supporting structured metadata. Synchronize its publication inventory with the README; do not silently add, omit, rename, or reclassify publications.
4. Confirm title, DOI, version, type, date and URL against the **specific authoritative publication record** when accessible. If only author-supplied evidence exists, preserve the supplied information and mark any unresolved independent verification accurately. A DOI is an identifier, not proof of scientific novelty, validation or peer review.
5. Distinguish **Zenodo DOI records**, books, conceptual works, technical reports, datasets, software, and unpublished projects. Do not automatically classify everything as academic research.
6. Preserve authorship, attribution, citations, provenance and existing valid links. Do not invent metadata, titles, descriptions, tests, websites, or DOI relationships.
7. If a publication is added or its title changes, update the README row and corresponding structured record, check for duplicates, and verify the saved files. Change other files **only if required**.
8. Keep the README concise and navigable. A full publication library should be complete, but not padded with repeated entries or marketing prose.

## Explicit non-goals and boundaries

- **Do not turn this repository into a website**, landing page, publication portal, web application or design project.
- **Do not edit `index.html`, CSS, sitemap, GitHub Pages, workflows, hosting or deployment** merely because publication data changes.
- **Do not add website sections or “live preview” features** without an explicit separate request.
- **Do not create a new DOI, Zenodo deposit, or public publication** without explicit authorization.
- Do not delete legacy files or change repository settings unless the owner specifically requests that action.
- When the user asks for a “repo link” or “preview” of the library, give `https://github.com/Joenasriani/joe-research-registry` (or its README anchor), not GitHub Pages.

## Current library example

The publication library currently includes six author-recorded works. The newest is **The Composer’s Prompt: Music Theory and Harmony for Computational Music Prompting**, a book associated by the author with DOI `10.5281/zenodo.23689714`. The earlier `10.5281/zenodo.23689713` is an unresolved historical identifier, **not a seventh publication**. Consult `registry.json` for evidence status, and do not infer a relationship between the two DOI identifiers without primary-record evidence.

## Change-control checklist

Before each commit: verify the exact user request; identify the minimum required files; preserve all existing valid publications; confirm the publication count and DOI/title pairs; keep README and JSON consistent; inspect the diff for unintended website or metadata changes. After each commit: reopen changed files and report what was actually saved, what remains unverified, and the direct repository link.

## Repository description (GitHub About field)

Suggested description:

> Joe Nasr’s publication library: research papers, technical reports and books, with Zenodo DOIs, publication links and researcher profiles. README-first index; not a website.

Only update the GitHub About/description field when an authorized tool supporting repository metadata changes is available; creating this document does not change that setting.

## Legacy website archive (28 October 2026)

The former GitHub Pages/HTML research website was preserved in branch [`archive/legacy-research-website-2026-10`](https://github.com/Joenasriani/joe-research-registry/tree/archive/legacy-research-website-2026-10) before cleanup. Website pages and the original HTML research note were removed from `main` to keep the main branch focused on the README publication library. **Do not restore or redeploy these pages unless explicitly asked.** This archive is preservation, not an endorsement or independent publication of those pages.

Some legacy supporting files and website infrastructure may still be present on `main`; inspect before any additional removal. Never delete unique research content without preserving a recoverable copy.
