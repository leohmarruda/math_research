# Organizing a mathematical research project

This is a reusable convention for projects that combine mathematical writing, exploratory notes, computation, external sources, and review. Adapt the directory names to the size of the project. The governing rule is that a new collaborator should be able to find the current claim, its proof, its evidence, its open gaps, and earlier versions without guessing which file is authoritative.

## 1. Give each kind of file one home

```text
project/
  README.md                 # Entry point and reading path
  STATUS.md                 # Current claims, gaps, and review state
  ROADMAP.md                # Prioritized next tasks and decision gates
  manuscripts/              # Current article or book drafts
  notes/                    # Working lemmas, examples, failed approaches
  reports/                  # Audits, comparisons, review responses
  scripts/                  # Source code for calculations and figures
  data/                     # Inputs, certificates, and reproducible results
  references/               # Papers and other external source material
  deliverables/             # PDFs and immutable packets sent to others
  archive/                  # Superseded drafts and historical records
  tmp/                      # Disposable local build and transfer work
```

Small projects can omit empty directories. A project with distinct research lines can use the same topic names under `manuscripts/`, `notes/`, `reports/`, `scripts/`, and `data/`. Prefer a shallow structure until a folder becomes hard to browse.

The `README.md` should point to one current manuscript or central theorem, the current status, the roadmap, and the reproduction instructions. Do not make a newcomer reconstruct these from a dated activity log.

## 2. Separate current truth from history

`STATUS.md` should answer, briefly:

- What is proved, conditional, conjectural, refuted, or merely observed?
- What assumptions and dependencies does each main claim require?
- What has been checked internally, by computation, and by independent reviewers?
- What is the next unresolved gap?

`ROADMAP.md` should list bounded tasks with an expected output, a reason to do them, and a stop or promotion condition. Keep exploratory ideas in a backlog rather than presenting them as active obligations.

Move dated progress entries to `archive/logs/` or a separate `RESEARCH_LOG.md` when they make the current status hard to read. A dashboard can provide a short overview, but it should link to the status rather than maintain a competing account. Record important changes in conclusions with dates and links to the supporting reports.

## 3. Name and version mathematical writing clearly

Keep one clearly identified **current working source** per manuscript. Put title, date, version, author or contributor status, and proof status near its beginning or in a neighboring `README.md`. Versioned snapshots are useful at review milestones; a directory named `revision2` that contains revision 3 needs an explicit note and should eventually be renamed when safe.

Use stable, descriptive names, for example `manuscripts/pairing/main.tex` and `notes/pairing/corner_case_2026-10-29.md`. Reserve dates for snapshots, reports, and records where chronology matters. Do not put every edit into a new `final_v2_revised` file. If the project uses Git, commit ordinary changes and create a tagged or archived snapshot for material sent for review.

Do not silently join two mathematical documents because they discuss the same result. A proof, a failed approach, an audit, and a reviewer response have different roles. Join them when one coherent exposition replaces the others, and retain links to the original evidence and decisions.

## 4. Keep computations auditable

Place source code in `scripts/`, input data and saved certificates in `data/`, and an explanation of the mathematical meaning in `notes/` or `reports/`. Each significant computational claim should identify:

1. The exact statement being checked and the scope it covers.
2. The command, environment or dependencies, input files, and expected output.
3. Whether the check uses exact arithmetic, interval bounds, exhaustive enumeration, or numerical sampling.
4. The result and any known limitations. A passing script does not automatically certify the surrounding analytic or topological argument.

Keep small decisive certificates and independent reproduction records. Large regenerable intermediates belong in a build or cache location and should be excluded from the source inventory. Document how to regenerate them before removing them.

## 5. Treat review packets as frozen snapshots

A packet sent to a reviewer may deliberately contain copies of a manuscript, scripts, data, and a manifest. Keep that packet intact even when its files duplicate the live tree: the copies show exactly what the reviewer received. Store the frozen ZIP or directory under `deliverables/` with a date or revision, and distinguish it from current source.

Do not edit an old packet in place to reflect later corrections. Issue a new revision with a short change log and preserve the earlier packet. Where practical, include a SHA-256 manifest and a `START_HERE.md` that states the review questions and reproduction steps. A favorable review of one version should not be silently attributed to a later version.

## 6. Archive deliberately

Archive a draft or branch when it is superseded, closed by a counterexample, or parked with a clear reentry condition. Preserve enough context to understand why: an `archive/README.md` or small index should name the former path, replacement, reason, and date. Do not archive a source that an active proof or reproduction procedure still requires merely because it is old.

Use `tmp/` only for genuinely disposable work. Before clearing it, check that unique source, results, and logs have been promoted to the appropriate active folder or an immutable packet. Temporary transfer helpers and build files should not be mistaken for research evidence.

## 7. Move files without breaking the project

For a significant reorganization:

1. Inventory paths and hashes, and identify links and scripts that refer to them.
2. Decide which copies are active sources, frozen snapshots, or disposable intermediates.
3. Make a path map; move in small batches within the project boundary.
4. Update relative links and script paths in active files. Leave frozen packets unchanged.
5. Verify hashes of files intended to be byte-identical, run relevant reproduction commands, and check links.
6. Update the root README and regenerate the inventory. Retain the move map until the new layout has been used successfully.

Use Git or a backup before broad moves. A generated inventory must state its inclusion rules and should exclude itself; otherwise its own hash is self-referential. Do not present an old manifest as current after later edits.

## 8. A light maintenance routine

At the end of a substantial research session, update the current status and roadmap only if the conclusion or priority changed. Promote useful notes and results from temporary work. At a review milestone, freeze a packet. Periodically check for stale links, duplicate delivery folders, superseded drafts still marked current, and inventory drift. Stop organizing when a reader can reliably answer what is current and reproduce the important claims.
