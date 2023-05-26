# The public report template for my personal use

This template is used to write in Japanese.

## Usage

1. Clone this repository.

2. Put the reference files (such as `*.bib`) in the `references` directory.

    - And use the reference file below:
        ```latex
        \bibliography{references/ref}
        ```

3. Write your report in `document.tex`.

4. Start the container
    ```bash
    docker-compose up -d
    docker compose exec lualatex latexmk
    ```
