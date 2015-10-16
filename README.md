### Sphinx <3 Markdown

This is an example repo that has both RST and MD processed by Sphinx.

You can see it rendered at https://sphinx-markdown-test.readthedocs.org/en/latest/

To try it our yourself:

```bash

mkvirtualenv sphinx-markdown
pip install -r requirements.txt
make html
open _build/html/index.html
```
