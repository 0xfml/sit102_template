# sit102_template
markdown report template.


Free to be used by students.



Requirements:
- pandoc
- texlive-full
- Eisvogel template

To create pdf.

```
pandoc report.md -o test_report.pdf \
--from markdown+yaml_metadata_block+raw_html \
--template ~/Downloads/eisvogel.tex \
--table-of-contents \
--toc-depth 1 \
--top-level-division=chapter \
--highlight-style breezedark 
```

Template link + instructions:
https://github.com/Wandmalfarbe/pandoc-latex-template#installation
