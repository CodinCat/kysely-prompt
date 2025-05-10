# kysely-prompt

[Kysely](https://github.com/kysely-org/kysely) is a very powerful query builder, but due to my skill issue, writing more complex queries can be frustrating sometimes.

This repo is just a prompt to help LLMs learn how to write queries using Kysely. All the examples are just copied and pasted from official documentation or GitHub issues, with some tweaks to save tokens. I hand-picked different examples to make sure they're diverse enough to cover most common use cases, and enough for AI to learn the patterns/APIs of Kysely. For now, it's PostgreSQL only.

## Usage

Just feed [this prompt](./kysely-postgresql.txt) to the AI of your choice, and then you'll have a personal Kysely expert to help you write queries.

The prompt has around 10,300 ~ 12,000 tokens. Note that on chatgpt.com, free users only get 8K context window. I recommend Gemini 2.5 Pro, which has 1M context window and you can use for free at https://aistudio.google.com/
