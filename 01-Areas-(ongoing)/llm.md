# Large Language Model (LLMs)

- Large Language Model (LLMs) is like a autocomplete feature on most phones.
- Analyzed a billions of pages of text to become an expert at predicting the next words in a sequence.

## Tokenization 🧱

- computers can't process letters or words, they only process numbers.
- Tokenization is process of breaking a words into smaller chunks called `tokens`.
- A token can be whole word, a part of words, even a punctuation mark.
- Each unique token is assign to specific number (an ID). The sentence `I love coding` might become [45, 1203, 6421].

## Context window 🪟

- This is model's memory for remember our conversation for short-term or long-term memory.
- its represents a number of tokens model can see and know our conversation a days ago.
- if context get too long model starts to `forget` the earliest parts.

### why it matters

- The context window includes everything in current session:
  - the instructions you gave at the start.
  - All the previous messages in the chat.
  - the response the AI is currently writing.

| Feature  | small context window                     | Large Context window                      |
| -------- | ---------------------------------------- | ----------------------------------------- |
| capacity | ~2000 tokens(a few pages)                | 100,000+ tokens (whole books)             |
| best for | quick question,short emails              | Analyzing long documents, coding projects |
| memory   | forgets the start of long charts quickly | Remember details from hours ago           |

## costs of tokens

- This is important to know that processing these tokens isn't free.
- Running the massive 'math engine' behind LLMs require a huge amounts of electricity and specialized computer chips (like GPU).

- Most AI companies charge users in one of two ways:
  - per 1,000 Tokens:i pay every token i send (my prompt) and every token AI sends back.
  - sometimes, the bigger context window i use, the bigger context window become expensive.
