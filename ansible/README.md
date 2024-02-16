# Tutorial Automation

The goal of this project is to use Jinja2 templates to convert from:
- A tutorial in markdown in separate files per step with sidecar JSON files for metadata
or
- A tutorial written in Google Docs exported to markdown with `claat`

converted to
- A single markdown file with metadata in the frontmatter and step tags in the body

## Work In Progress

- [] write Jinja2 template from current working codelabs final markdown
    - [] convert existing hugo template into a more modular Jinja2 template that can be updated with YAML for congrats, and other components