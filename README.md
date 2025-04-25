# Inappropriate Words Lists

A multilingual collection of profanity, slurs, and inappropriate terms for content moderation systems. This repository provides word lists in multiple languages to help developers implement effective content filtering.

## About

This project aims to provide comprehensive lists of inappropriate words across different languages, organized in a consistent format. Each file contains terms that might be filtered in forums, chat applications, username validation, or other content moderation contexts.

The lists are:
- Organized alphabetically
- Formatted with one word per line
- Named according to BCP 47 language tags

## Available Lists

Currently, this repository includes inappropriate word lists for:

- Dutch (nl-NL.txt)
- Frisian (fy-NL.txt)
- Afrikaans (af-ZA.txt)

## Implementation Considerations

When using these lists for content moderation:

1. **Context matters**: Consider the context in which terms appear
2. **Partial matches**: Be careful with substring matching to avoid false positives
3. **Variations**: Users may try to evade filters with alternate spellings or character substitutions
4. **Regular updates**: Language evolves, and new terms emerge regularly

## Contributing

Contributions to expand or improve the word lists are welcome. When contributing:

1. Maintain alphabetical ordering
2. Follow the one-word-per-line format
3. Use UTF-8 encoding
4. Add new languages using the appropriate BCP 47 language tag

## Disclaimer

These lists are provided for legitimate content moderation purposes. The inclusion of words in these lists is not an endorsement of their use. The maintainers of this repository do not condone the use of these terms.
