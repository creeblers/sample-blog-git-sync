# Export Information

This export was generated on 2025-08-04 05:11:25

## Summary

- **Database**: Creeble Sample
- **Database ID**: `01986502-6c98-705e-a638-cc0bb8cae8be`
- **Created**: 2025-08-01T09:41:54.000000Z
- **Last Edited**: 2025-08-04T05:11:21.000000Z
- **Total Pages**: 10
- **Pages with Content**: 10
- **Child Databases**: 0
- **Export Format**: Markdown

## Database Description

Demo Projects

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
