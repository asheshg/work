# Banking concepts migration — 2026-11-21

| Source repository | Imported commit | Destination |
|---|---|---|
| asheshg/p1tch | 32261187a767c3cb13543a57ca0c4b4bea1c7191 | projects/p1tch |
| asheshg/landing-page | 3d2bdd25fb464edd2d71f92fd9a906e7cf977ca7 | projects/landing-page |

Main-branch histories are retained through unsquashed Git subtree merges. Project code is unchanged. Both GitHub Actions jobs passed JavaScript syntax and required-entry-file checks. Deployed HTML matched the imported files after normalizing checkout line endings.

The existing `landing-page-concept` Vercel project now uses this repository, root `projects/landing-page`. Its production domain was retained. A new `p1tch` Vercel project uses root `projects/p1tch`. Both are static deployments with framework Other, no build or install command, and output directory `.`.

Original source repositories and GitHub Pages sites remain available as rollback copies, with successor notices. Issues, PRs, releases, tags and other branches were not transferred. Update source here for future Vercel deployments; the old Pages sites do not automatically follow this repository.

Three previously inventoried repositories remain unavailable due to GitHub trademark blocks: `sbi-recreation`, `bank-landing-page`, and `bank-landing-page-designcode`. They have not been imported, renamed, republished or deleted.

Prototype banking links, external image URLs, third-party scripts and interactions were not repaired or comprehensively tested. Migration checks do not establish that those integrations work.
