# Export Information

This export was generated on 2025-07-26 08:01:17

## Summary

- **Database**: Sample - Blog
- **Database ID**: `019845b0-9c63-7227-bce7-fb0e9e4db30a`
- **Created**: 2025-07-26T07:44:19.000000Z
- **Last Edited**: 2025-07-26T08:01:04.000000Z
- **Total Pages**: 4
- **Pages with Content**: 4
- **Child Databases**: 0
- **Export Format**: Markdown

## Database Description

Blog site demo

## Files

- `pages/` - Pages database entries: `[page-slug].md`
- `[database-slug]/` - Other database folders: `[page-slug].md`
- `export-info.md` - This file with detailed export information

## Usage

Each page is exported as a separate Markdown file with:
- YAML frontmatter containing metadata and properties
- Page title as H1 header
- Content section with the page content converted from HTML

## Folder Structure

- **'Pages' database** → `pages/[page-slug].md`
- **Other databases** → `[database-slug]/[page-slug].md`

## Notes

- Only entries with actual content in `html_content` are exported as `.md` files
- Page titles and database names are converted to URL-friendly slugs
- All Notion properties are preserved in YAML frontmatter
- HTML content is converted to clean Markdown using league/html-to-markdown
- **Export files are automatically deleted after download** to save storage space
