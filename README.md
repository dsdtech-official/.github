# `.github`

Organization-wide defaults for [DSD TECH](https://github.com/dsdtech-official).

| Path | What it does |
|---|---|
| `profile/README.md` | Rendered as the organization profile at <https://github.com/dsdtech-official> |

Default issue forms, a contribution guide and a security policy will be added here once
there is more than one repository for them to apply to.

## How the defaults work

A repository that ships its own copy of one of these files always wins. This
repository is the **fallback**, used only for repositories that have none.

Within a single repository, GitHub looks in `.github/`, then the repository root,
then `docs/`. Only if none of those has the file does it fall back to this
repository.

That fallback is why anything placed here has to suit **every** repository in the
organization, not just the one it was written for.

`LICENSE` is **not** inherited this way — every repository needs its own.

Reference:
[organization profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) ·
[default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
