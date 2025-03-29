# kysely-prompt

[Kysely](https://github.com/kysely-org/kysely) is a very powerful query builder, but due to my skill issue, writing more complex queries can be frustrating sometimes.

This repo is just a prompt to let LLMs learn how to write queries using Kysely. All the examples are just copied from the official documentation, with some modifications to save tokens. I hand-picked different examples and tried to make sure they are diverse enough to cover most common use cases, and enough for AI to learn the patterns/APIs of Kysely. For now it's PostgreSQL only.

It's around 8,000 ~ 9,300 tokens. Note that on chatgpt.com free users only get 8K context window.

## Usage

Just feed [this prompt](./kysely-postgresql.txt) to the AI of your choice, and now you have a personal Kysely expert to help you write code with Kysely.
