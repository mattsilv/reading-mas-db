# Reading App Database

This repository contains structured data for the Reading App for Kids. It supports multiple languages and lessons.

## Directory Structure

- `locales/`: Contains subdirectories for each locale.
  - `en/lessons/`: Contains lesson files for English.
  - `es/lessons/`: Contains lesson files for Spanish.
  - `fr/lessons/`: Contains lesson files for French.

## Adding a New Lesson

1. Create a new JSON file in the appropriate locale's `lessons` directory.
2. Follow the structure of existing lesson files.

## Supported Locales

- `en`: English
- `es`: Spanish
- `fr`: French

## Example Lesson File Structure

```json
{
  "lesson": "LESSON_NAME",
  "words": [
    {
      "letter": "LETTER",
      "word": "WORD",
      "definition": "DEFINITION"
    }
  ]
}
