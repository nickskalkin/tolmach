# Tolmach

A tiny utility that helps me populate my Anki collection of German words using the OpenAI API.

## Installation

Install ruby version specified in `.ruby-version` file and then:

```
bundle
```

Set required environment variables:

- `ANKI_MEDIA_PATH` - path to the `collection.media` directory. In my case it is located in `~/Library/Application Support/Anki2/User 1/collection.media/`.
- `DECK_OUTPUT_PATH` - path to the output csv that contains anki cards.
- `OPENAI_API_KEY`

## Usage

```
./tolmach [optional:german word]
```
