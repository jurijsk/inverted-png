# PNG images inverted by muPdf mutool when converting pdf to html

I'm using mutool (v 1.19.0) to convert pdf to html using the following command:

.\mutool.exe convert -o output.html -O preserve-images .\input.pdf
It converts the file to html and embeds images as dataUrl.

The problem is that often, but not for all pngs, they end up inverted.

They appear inverted on the page and if I store the separately (both in the broser and via code).

Is there there something with mutool wrong? Or there is a bit in png i need to flip?

Let me know.

Download muPdf with mutool [here](https://www.mupdf.com/downloads/index.html)
