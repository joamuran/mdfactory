---
pdf-engine: xelatex
from: markdown
data-dir: /usr/share/mdfactory/
#template: /tmp/Pandoc-Emojis-Filter/template.tex
template: templates/eisvogel.latex
number-sections: true
highlight-style: tango
syntax-definition: /usr/share/mdfactory/languages/dart.xml
filters:
   - pandoc-latex-environment
   - mermaid-filter
#   - /tmp/Pandoc-Emojis-Filter/emoji_filter.js
