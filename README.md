# kysely-prompt

[Kysely](https://github.com/kysely-org/kysely) is a very powerful query builder, but because of my skill issue, it was frustrating when I first started using it. Sometimes I just don't know how to write the query I want with Kysely. 

This repo is just a prompt to let LLMs learn how to write queries using Kysely. All the examples are just copied from the official documentation, with some modifications to save tokens. I hand-picked different examples and tried to make sure they are diverse enough to cover most common use cases, and enough for LLMs to learn the patterns/APIs of Kysely.

Some stuff like migration or merge are not included because I just don't need them (yet).

It's around 7800 tokens according to [OpenAI's tokenizer](https://platform.openai.com/tokenizer).

## Usage

Just feed [this prompt](./kysely-postgresql.txt) to the AI of your choice and then ask it to write whatever query you want.
