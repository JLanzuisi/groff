groff-repo(1)               General Commands Manual              groff-repo(1)



Name
       groff-repo. This is a github repository where I mantain my groff files.

Description
       This repo holds all the files I write in groff.  I'm still learning, so
       expect them to have errors.  The main macro set used is MOM.  There may
       be some ms or man macros.  The next section lists some important files.

Files
       preamble.groff
              A  file that has all the macros I normally use, they usually de-
              scribe formatting.  This file gets cat(tenated)  with  the  main
              file I write in, and the result is piped into groff.

       postamble.groff
              Like  the  above,  excepct  for  stuff I always want at the end.
              Things like the .TOC macro or the license notice.

       *.full.groff
              These hold the result of cat, see above.  It is useful  to  have
              this in case I need to share the groff file, this way I can send
              a complete file.

Building
       wip

Other
       If you are a TeX convert like me, check a tool on ctan  called  tex2re-
       fer.  It's an awk script to convert your existing TeX .bib files to re-
       fer.



                                     2020                        groff-repo(1)
