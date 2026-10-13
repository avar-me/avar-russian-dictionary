# bots_data

Verbatim re-dump of `diction.py`/`rudiction.py`'s `dict_list` against the
`all.txt`/`ruall.txt` currently running on the `avar.me` server (behind
`@avarme_bot` and `@ruavarme_bot`), using the unmodified parsing scripts.

Same `word:form1,form2,...:translation` format as the files one level up, but
refreshed from the live server — those had drifted slightly (a past edit to
`collect_data()`'s wording for entries with no direct translation changed
`;` to `:`, affecting ~1.5-2% of lines) and no longer matched what the bots
actually reply with.

Used to seed the Telegram Serverless ports of these two bots
(`avarme_bot`/`ruavarme_bot` projects) — not a general-purpose dictionary
source, just a seed snapshot for that migration.
