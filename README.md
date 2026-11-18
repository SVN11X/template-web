# CHANGE-ME

TODO(owner): What this is, in one sentence.

## For whom

TODO(owner): Who uses it and in what situation.

## Use it

TODO(owner): How to install or open it, with a minimal example.

## How it works

`docs/how-it-works.md` explains the main flow from start to finish, each part with its path, where to start reading the code and how to check that it works.

## Status

Draft.

## Layout

- `src/`: Source of the site or app.
- `assets/`: Static media used by the site.
- `tests/`: Automated tests.
- `scripts/`: Developer scripts. Optional.
- `docs/`: goals, glossary, assumptions, decisions and specs.

## Contributing

Tasks use the Task issue form. Pull requests follow `.github/pull_request_template.md`. Rules for people and AI tools are in `AGENTS.md`.

## Standard

This repository follows `SVN11X/standards@v1` with the `web` profile. `AGENTS.md` is generated, so do not edit it by hand. To regenerate it or run the check locally:

```bash
pip install pyyaml
git clone --depth 1 --branch v1 https://github.com/SVN11X/standards .standards
python .standards/scripts/standard.py agents .
python .standards/scripts/standard.py check .
```

## License

MIT. See LICENSE.
