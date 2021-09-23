# Flynn-Moranville-s-ALGOL-M-source-code
OCR'd the 16 PDF Pages to re-create Source by using Irfanview's KADMOS OCR package.

I burst the PDF with pdftk in Debian 9.x to get individual PDF pages at 72 DPI,
then converted the 72 DPI to 400 DPI and created a *.TIF of each page.

$ pdftk document.pdf burst
$ convert -density 400 pg_001.pdf -depth 8 pg_001.tif 

Corrected as many errors as possible, but there are several remaining.

I've searched the complete document for "0" vs "o", "i" vs "l", "1" vs "l", and lots of other
combinations.  There are errors in the actual pneunomics (page 13), as some of those are hard to
read. (bli vs bii vs b1i and sor vs gor vs aor). But, i don't think any other OCR software would
have worked as well as KADMOS, on these source documents.  I've previously tested Tesseract,
and TextBridge Classic against KADMOS and KADMOS has done a better job.



