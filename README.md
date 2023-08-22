# Applied Computing Style Guides

This repo collects the various style and linting rules used by [Applied Computing Research
Labs](https://appliedcomputing.io) for its various projects and languages.  Instead of enumerating a bunch of style
rules that we expect people to follow in our repos, we instead enforce the styles that we care about via linting rules.
Therefore, the source of truth for our currently-accepted styles are what is contained in this repo.  These are living,
evolving rulesets that may change in the future as we get better at our jobs (or our opinions change :D).

## pre-commit

We use [pre-commit](https://pre-commit.com) to enforce these rules whenever possible.  If you are working in one of
our repos, we encourage you to install pre-commit so that checks can be performed before violating code is pushed.

## License

It is unclear to me that "a list of linting configuration rules" can be copyrighted in any meaningful way, but in the
event that it can, you can consider these rules to be in the public domain, e.g. CC0 1.0 Universal (see the accompanying
[license file](LICENSE.md)).
