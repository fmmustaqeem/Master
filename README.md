# FM Master

**FM Master** is the central documentation and coordination repository for the FM project ecosystem. It is intended to keep the account structure, repository inventory, project boundaries, audit findings, and future integration plan in one place.

> **Current phase:** Read-only repository audit and documentation. No repository changes, migrations, merges, deployments, or automated workflows are authorized as part of the audit.

## Mission

- Maintain a clear inventory of the FM GitHub ecosystem.
- Document what each account and repository is responsible for.
- Preserve the identity and boundaries of individual FM projects.
- Record verified status, dependencies, risks, and next steps.
- Prepare a future integration plan only after the repository audit is complete and reviewed.

## GitHub account scope

The current audit scope covers **four GitHub accounts and 33 repositories**:

1. [fmmustaqeem](https://github.com/fmmustaqeem)
2. [wakilmustaqeem](https://github.com/wakilmustaqeem)
3. [hidayattubeofficial-ai](https://github.com/hidayattubeofficial-ai)
4. [fmaigames](https://github.com/fmaigames)

The repository inventory is being collected account by account. Repository ownership, visibility, purpose, default branch, README, releases, packages, issues, pull requests, and existing automation should be documented from available evidence. Counts and statuses must be updated only when verified.

## Project boundaries

These project identities must remain distinct during the audit and planning process:

| Project | Purpose |
|---|---|
| **FM Commerce** | Digital products, software, tools, creator resources, and digital services. It is not a physical-goods marketplace. |
| **FM Gifts & Luxury Watches** | Separate physical-goods gift and luxury-watch storefront. |
| **FM Market** | Separate FM marketplace project. |
| **FM B2B Market** | Separate business-to-business marketplace project. |
| **Fm-computer** | Separate computer-related project. |
| **FM AI Games** | Game-focused project/account under fmaigames. |
| **HidayatTube AI** | Separate project/account under hidayattubeofficial-ai. |
| **DroidRunner / FM Droid** | Android-based runner and app work, including the fmmustaqeem/DroidRunner repository. |

A shared FM ecosystem does not mean these products should be merged into one indistinguishable product. Any future control panel or integration must preserve separate project identities, repositories, ownership, and permissions.

## Known project notes

### FM Commerce

- Live site: [fm-tech.byethost15.com](https://fm-tech.byethost15.com)
- Main repository: [fm-commerce-platform](https://github.com/fmmustaqeem/fm-commerce-platform)
- The platform is for digital goods and services.
- Large video files should be hosted externally (YouTube is the preferred option); the website should use links or embeds rather than storing large video files on the free host.
- The site's language direction is English-first, with optional Urdu support.
- Do not confuse FM Commerce with FM Gifts & Luxury Watches or the separate FM Market projects.

### FM Gifts & Luxury Watches

- Storefront: [giftsandwatch.byethost18.com](https://giftsandwatch.byethost18.com)
- Repository: [fm-gifts-luxury-watches](https://github.com/fmmustaqeem/fm-gifts-luxury-watches)
- This is a separate physical-products storefront, not the FM Commerce digital marketplace.

### DroidRunner / FM Droid

- Target repository: [fmmustaqeem/DroidRunner](https://github.com/fmmustaqeem/DroidRunner)
- The work includes an Android runner environment and an FM Droid app build.
- The documented device/testing context includes a ZTE Z2352N running Android 13 (API 33) with a Unisoc T820 platform.
- Earlier P0 testing was reported as successful; retain exact run links and logs when adding a formal test record.
- Do not assume a build is released or deployed unless a release or deployment is verified.

## Audit rules

1. **Read-only:** inspect and document; do not edit repositories during the audit.
2. **No GitHub Actions:** do not trigger, rerun, or add Actions workflows for this audit.
3. **No spending:** prefer free and open-source approaches; do not introduce paid services without explicit approval.
4. **No unapproved changes:** no commits, branches, pull requests, merges, deployments, secrets, settings, or configuration changes during the audit.
5. **Evidence first:** distinguish verified facts from user-provided notes, assumptions, and items still requiring verification.
6. **Keep boundaries:** do not combine separate accounts or projects merely because they share the FM name.
7. **No background monitoring:** this is a one-time, consolidated review unless monitoring is explicitly requested again.

## Audit status

- [x] Master repository created.
- [x] Initial repository details recorded: public repository, main branch, one initial commit, and README as the only file shown in the supplied repository snapshot.
- [ ] Complete read-only inventory of all 33 repositories across the four accounts.
- [ ] Record repository-level findings and outstanding risks.
- [ ] Produce the consolidated audit report.
- [ ] Propose a future architecture and integration plan for review.
- [ ] Obtain explicit approval before any implementation or repository mutation.

## Future direction

After the inventory is complete, this repository can hold the approved FM Master Plan: a documented architecture for a unified overview or control plane that connects the relevant projects without erasing their independent identities. No integration or migration should begin until the audit findings and proposed plan have been reviewed and explicitly approved.

## Repository information

- Repository: [fmmustaqeem/Master](https://github.com/fmmustaqeem/Master)
- Visibility: Public
- Default branch shown in the supplied repository snapshot: main
- Initial commit shown in the supplied snapshot: 6dc018daae66b2d7b7189ea7bc239eaf4eaa241e
- Current purpose: FM ecosystem documentation and master planning

---

*This README is a working record. Update it as repository facts are verified; do not present pending audit items as completed work.*
