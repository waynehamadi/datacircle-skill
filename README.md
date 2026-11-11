# Datacircle skill

Find the best GTM APIs. We benchmark all the GTM APIs and we put the results on our website: https://datacircle.dev

## Install

Copy `SKILL.md` into your agent's skills folder, for example `.claude/skills/datacircle/SKILL.md`. Any agent that reads the Agent Skills format can use it.

## Use

Ask your agent to compare or price a GTM API. The skill downloads https://datacircle.dev/datacircle.json, one row per plan with its price, score, rate limits and fields. It needs no key and no account.

The same data is open as an API at https://api.datacircle.dev/v1 (spec: https://api.datacircle.dev/v1/openapi.json).

## License

MIT
