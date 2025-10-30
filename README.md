# CogSci Conference Proceedings Template

A Typst template for submitting papers to the [Cognitive Science Society](https://cognitivesciencesociety.org/) annual conference. This template aims to be a visual clone of the official LaTeX template.

## Usage

You can use this template in the Typst web app by clicking "Start from template" on the dashboard and searching for `cogsci`.

Alternatively, you can use the CLI to kickstart a new project on your computer:

```bash
typst init @preview/cogsci
cd cogsci
```

## Configuration

The template exports the `cogsci` function with the following named arguments:

- `title`: Paper title (content or string)
- `authors`: Array of author dictionaries with `name`, `email`, and `affiliation` fields
- `anonymous`: Whether to hide authors for blind review (boolean, default: `true`)
- `final-submission`: Alternative to setting `anonymous: false` (boolean, default: `false`)
- `abstract`: Abstract content
- `keywords`: Array of keywords (strings)
- `bibliography`: Result of calling `bibliography("your-file.bib")` or `none`
- `acknowledgments`: Acknowledgments section (only shown in non-anonymous mode)

The template creates a two-column paper with:
- 7" � 9.25" text area with 0.25" column separation
- Times New Roman 10pt font with proper spacing
- Three levels of headings (centered, left-aligned, and run-in)
- APA-style citations and references
- Properly formatted figures, tables, and footnotes

## Page Limits

- **Initial submission**: 6 pages maximum (all content)
- **Final submission**: 6 pages for main text + 1 page for acknowledgments and references

## License

MIT License - See LICENSE file for details.
