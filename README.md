# Random Word Generator

A small command-line tool to generate random words.

## Usage

Run the generator with Python:

```bash
python3 random_word_generator.py -n 5
```

Options:
- `-n`, `--number`: number of random words to generate.
- `-u`, `--unique`: generate unique words when possible.
- `-f`, `--file`: load words from a custom file (one word per line).

## Examples

Generate 3 random words:

```bash
python3 random_word_generator.py -n 3
```

Generate 5 unique random words from a file:

```bash
python3 random_word_generator.py -n 5 -u -f words.txt
```

## Local ZIP download

Run the local server and download the zip file from your browser:

```bash
python3 serve_zip.py
```

Open `http://localhost:8000/` and click the download link.
