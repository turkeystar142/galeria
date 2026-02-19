# The Flash Drive

A simple gallery website that serves to display memories. 

## Quick Start

Start the Hugo development server:

```bash
hugo server -D
```

Then open `http://localhost:1313` in your browser.

## Build

```bash
hugo
```

## Adding a new entry

Run the following command:

```bash
hugo new --kind memory content/en/{insert_new_name}/index.md
```

Update the template article that was created, and insert the relevant jpg into the same directory that was just created.

Create the same article in spanish within `content/es/{insert_new_name}`
