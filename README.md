


# Machine Translation with Transformers

This repository contains code for machine translation using Transformers. The code is based on the MarianMT model, which is a pre-trained Transformer model for machine translation. You can use this code to translate sentences between any two languages supported by the MarianMT model.

## Prerequisites

Before using the code, make sure you have the following Python libraries installed:

- `torch`
- `transformers`
- `nltk`

You can install them using `pip`:

```bash
pip install torch transformers nltk
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/machine-translation-transformers.git
cd machine-translation-transformers
```

2. Run the translation script:

```bash
python translate.py --source-language <source_language> --target-language <target_language> --input-file <input_file> --output-file <output_file>
```

Replace the following placeholders:
- `<source_language>`: The source language code (e.g., "en" for English).
- `<target_language>`: The target language code (e.g., "fr" for French).
- `<input_file>`: Path to the file containing sentences you want to translate.
- `<output_file>`: Path to the output file where translated sentences will be saved.

## Example

Here's an example of how to translate sentences from English to French:

```bash
python translate.py --source-language en --target-language fr --input-file input.txt --output-file output.txt
```

## Supported Languages

The MarianMT model supports a wide range of languages. You can find the full list of supported languages in the official MarianMT documentation [here](https://marian-nmt.github.io/docs/marian/description/#supported-languages).


## Acknowledgments

- This code is based on the MarianMT model developed by the Marian-NMT team. You can find more information about MarianMT [here](https://marian-nmt.github.io/).

Feel free to contribute to this project or report issues if you encounter any problems.


