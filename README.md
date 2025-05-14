# Manage my resume   
[![Generate resume.pdf](https://github.com/yk-jp/resume/actions/workflows/main.yaml/badge.svg?branch=master)](https://github.com/yk-jp/resume/actions/workflows/main.yaml)

## How to Generate the PDF

1. **Install dependencies**  
   If you haven't already, install the dependencies:

   ```sh
   yarn install
   ```

2. **Generate the PDF**  
   To generate the PDF from the Markdown file, run:
   ```sh
   yarn generate
   ```
   This will create a `resume.pdf` file based on `resume.md`.

## Project Structure

- `resume.md` — The resume content in Markdown.
- `config/` — Configuration files for formatting and styling the PDF.
- `package.json` — Project dependencies and scripts.

## License

MIT
