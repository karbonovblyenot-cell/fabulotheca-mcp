# Fabulotheca — MCP search server for folklore & fairy-tale studies

Fabulotheca (https://fabulotheca.org/en) is a search service over a scholarly corpus on Russian and European folk tales and folklore studies: 2,000+ full-text sources and 5,000+ catalogued works, with tale-type indexes (ATU / SUS). It returns **verbatim fragments with exact bibliographic references** — it does not paraphrase and does not serve files.

Free until 1 January 2027. Texts are machine-recognised; check quotations against the original.

## Connect
It is a remote MCP server (Streamable HTTP). Each user gets a **personal URL** of the form `https://fabulotheca.org/mcp/<personal-key>` (the key acts as the password).

1. Apply at https://fabulotheca.org/en/apply (English form; a short application).
2. You receive the personal link in your account straight after the application.
3. Add it as a custom connector / remote MCP server in your AI client — step-by-step guides: https://fabulotheca.org/en/connect

There is no public anonymous endpoint, so catalogs cannot connect to it; access is by application. Server card: https://fabulotheca.org/.well-known/mcp/server-card.json

## Tools
`account`, `search`, `expand`, `get_context`, `where`, `collection_stats`, `guide` — search, show a list of sources, expand chosen ones into verbatim fragments, get surrounding context, and tell where a source can be obtained.

## Languages
Interface: English and Russian (application form, account, website search, connection guides). Corpus: mostly Russian, part in European languages.

## Contact
alyzlova@rambler.ru · Website: https://fabulotheca.org/en
