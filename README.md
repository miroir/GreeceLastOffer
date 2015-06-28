# Last Offers
Split and cleaned versions of the "Last Proposals" of the Troika and the Greek government.

Based on the PDFs from:
- http://blogs.ft.com/brusselsblog/2015/06/26/leaked-greeces-new-bailout-counterproposal/
- http://blogs.ft.com/brusselsblog/2015/06/25/leaked-greece-bailout-plan-sent-to-eurogroup/

##Differences in the proposals
See https://github.com/miroir/GreeceLastOffer/tree/master/Diffs for screenshots with highlighted differences.

###Verify the differences yourself
Tools to highlight differences in text files
- **Windows**: Winmerge http://winmerge.org/
- **Mac**: Diffmerge http://www.sourcegear.com/diffmerge/
- **Linux**: you probably know what to do

##Content
Greek offer in `greek*` , Troika offer in `troika*`
For the originally extracted content please refer to the PDF version or the unedited text files `greece.txt` and `troika.txt`.

The PDF files were first converted with `pdftotext` and split with `csplit --digits=2  --quiet --prefix=greece greece.txt "/CHAPTER/" {"*"}` (the *CHAPTER* tag was inserted before splitting - it is not part of the original content). 

##Note
Although `miroir` is the French word for `mirror` (and `Spiegel` is the German word for `mirror`) **I am not in any way related to FT's Peter Spiegel**!
