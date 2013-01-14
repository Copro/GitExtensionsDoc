Git Extensions Manual
=====================

This repository contains the new Git extensions Manual. Feel free to help us improve this manual by sending pull requests
or by opening issues.

HTML Help Files
---------------

Download http://www.microsoft.com/en-us/download/details.aspx?id=21138.

To build the file, use `makeHTMLHelp.cmd`

PDF
---

To use the PDF builder, you'll need to install:

* rst2pdf `easy_install rst2pdf`
* pil `easy_install pil`

Also add this `,'rst2pdf.pdfbuilder'` to the source/cofig.py file at the line 28. Then run `make.cmd pdf`.

HTML
----

Simply run `make.cmd html`.
