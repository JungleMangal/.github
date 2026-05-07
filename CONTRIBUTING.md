# Contributing to E-Segments projects

Thank you for considering a contribution. This file applies to every
repo in the JungleMangal org unless that repo overrides it.

## Quick rules

1. **Open an issue first** for non-trivial changes. We may already be
   working on it, or have a different direction in mind.
2. **One PR per concern.** Don't bundle a refactor with a feature with
   a typo fix.
3. **Tests required** for behavior changes. Bug fixes need a regression
   test.
4. **Match existing style.** No reformatting drives unrelated to your
   change. `cargo fmt` / project linters are fine.
5. **No AI attribution in commits.** No `Co-Authored-By: Claude` etc.

## Workflow

```
git checkout -b feature/short-description
# ... commits ...
git push -u origin feature/short-description
gh pr create
```

CI must pass. Reviewers may ask for changes; please rebase rather than
merge main into your branch.

## Commits

Conventional Commits where reasonable:

- `feat:` new functionality
- `fix:` bug fix
- `refactor:` no behavior change
- `docs:` documentation only
- `chore:` tooling/build
- `test:` test changes only

## Licensing

By submitting a PR you agree that your contribution is licensed under
the same dual MIT/Apache-2.0 terms as the host repo.

## Reporting bugs

See each repo's issue templates. Include reproduction steps, expected
vs. actual behavior, and version info (`fang-kit --version`,
`git --version`, OS, etc.).

## Security

Do **not** open public issues for security bugs. See
[SECURITY.md](./SECURITY.md).
