# Pretext Proof of Concept Testing

This repository exists to try out some things.  Currently the document was built using

1. Creating a new book with

```bash
pretext new book
```

2. Editing `main.ptx` to include two sage (python) cells.  The first cell imports numpy.  The second using numpy without importing it.

3. Building to `output/web`

```
pretext build web
```

    In this version, one must explicitly run the first cell in order for the second to work without error.

4. Copying `output-web` to `output/web-alt` to show a way that HTML could allow for the first cell to be autoevaluated so that the second cell can be exectuted with out manually executing the first.

    Now the first cell is autoevaluated, so the second cell can be run immediately.

Visit <https://pretextbook.org/documentation.html> to learn more about pretext.