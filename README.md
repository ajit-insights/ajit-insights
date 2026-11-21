# Ajit

I build data tools and apps for my own work and research.
Data, software and careful checking: I like systems where every number traces back to a source.

## What I build
- **Pramāṇa**: a research data platform. Public records going back decades, scanned documents turned into structured, queryable data, with every gap listed and not hidden.
- **Pratistha**: a personal work system: tasks, files, orders, reports.
- **Sūtra**: an Android app that runs my day: agenda, meetings, tasks, feedback, offline first.
- **Saṅgraha**: a query page for a SQLite database. One HTML file, no server, saved queries, runs in your browser.
- **Smṛti**, **Prajñā**, **Prārambh**, **Prakṛti**: memory, learning, household finance and a balcony farm.

## Working with AI
I build with Gemini and Claude: Gemini inside the systems I run, Claude as my engineering partner. My focus is making them dependable, and I've learned that evaluation is most of the work.

- **Check everything against the source.** Every model extraction from scanned documents is compared with records I already trust, and I report agreement rates. A rule-based parser I validated on about 5,000 checked records matched in over 99% of fields, so I used it instead of paying for a model call per document.
- **Use a model only where it earns its cost.** Rules where rules work. AI for the messy parts, with confidence checks, metered cost and pacing around rate limits.
- **Retrieval that cites or refuses.** A question-answering system over about 200,000 passages: vector and keyword search merged and reranked, numbers answered by read-only database queries, and answers with sources, or a refusal when the sources don't say.
- **People stay in charge.** Changes come with a dry run and an undo file, suggestions need my approval, and I decide which data may ever reach a model.

I don't take AI output on trust. I take it when I can show it holds up.

## Open source
I'm a die-hard fan of open source software, and most of what I build stands on it: Python, SQLite, Kotlin, Syncthing and many others.
See the full list of what I use [here](list_open_source_apps.md).

## How I work
Python, SQLite, Kotlin/Jetpack Compose, and Gemini for the messy extraction work. I check results against the source documents before I trust them.

## Find me
[LinkedIn](https://www.linkedin.com/in/ajit123) · [Kaggle](https://www.kaggle.com/qwaazs)

*Views are my own.*
