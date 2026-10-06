# Mirqat

RAG system over Hanbali fiqh and hadith, in Arabic and English. Live at [mirqat.app](https://mirqat.app). Coming soon on iOS.

Ask a question and Mirqat answers from 52 books, citing the book, volume and page for each point. If the books don't cover the question, it says so. It's a research aid for reading the sources and does not issue fatwas.

## How it works

- Vector search and full-text search run over the same passages, and their results are merged into one ranking.
- Arabic queries match with or without diacritics.
- Each answer is checked against the passages it cites before it's shown.

## Built with

Python, FastAPI, PostgreSQL, pgvector, Gemini, Docker
