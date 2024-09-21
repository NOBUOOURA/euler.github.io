## Welcome to Nobuo OURA's GitHub Pages

You can use the [editor on GitHub](https://github.com/NOBUOOURA/euler.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


<p><a href="mailto:foo@bar.baz">mailto:foo@bar.baz</a></p>
<p><a href="mailto:a.b-c_d@a.b">mailto:a.b-c_d@a.b</a></p>
<p><a href="mailto:a.b-c_d@a.b">mailto:a.b-c_d@a.b</a>.</p>
<p><a href="mailto:a.b-c_d@a.b">mailto:a.b-c_d@a.b</a>/</p>
<p>mailto:a.b-c_d@a.b-</p>
<p>mailto:a.b-c_d@a.b_</p>
<p><a href="xmpp:foo@bar.baz">xmpp:foo@bar.baz</a></p>
<p><a href="xmpp:foo@bar.baz">xmpp:foo@bar.baz</a>.</p>


Defines all Languages known to GitHub.

 fs_name               - Optional field. Only necessary as a replacement for the sample directory name if the
                         language name is not a valid filename under the Windows filesystem (e.g., if it
                         contains an asterisk).
 type                  - Either data, programming, markup, prose, or nil
 aliases               - An Array of additional aliases (implicitly
                         includes name.downcase)
 ace_mode              - A String name of the Ace Mode used for highlighting whenever
                         a file is edited. This must match one of the filenames in https://gh.io/acemodes.
                         Use "text" if a mode does not exist.
 codemirror_mode       - A String name of the CodeMirror Mode used for highlighting whenever a file is edited.
                         This must match a mode from https://git.io/vi9Fx
 codemirror_mime_type  - A String name of the file mime type used for highlighting whenever a file is edited.
                         This should match the `mime` associated with the mode from https://git.io/f4SoQ
 wrap                  - Boolean wrap to enable line wrapping (default: false)
 extensions            - An Array of associated extensions (the first one is
                         considered the primary extension, the others should be
                         listed alphabetically)
 filenames             - An Array of filenames commonly associated with the language
 interpreters          - An Array of associated interpreters
 language_id           - Integer used as a language-name-independent indexed field so that we can rename
                         languages in Linguist without reindexing all the code on GitHub. Must not be
                         changed for existing languages without the explicit permission of GitHub staff.
 color                 - CSS hex color to represent the language. Only used if type is "programming" or "markup".
 tm_scope              - The TextMate scope that represents this programming
                         language. This should match one of the scopes listed in
                         the grammars.yml file. Use "none" if there is no grammar
                         for this language.
 group                 - Name of the parent language. Languages in a group are counted
                         in the statistics as the parent language.

 Any additions or modifications (even trivial) should have corresponding
 test changes in `test/test_blob.rb`.

 Please keep this list alphabetized. Capitalization comes before lowercase.
---
1C Enterprise:
  type: programming
  color: "#814CCC"
  extensions:
  - ".bsl"
  - ".os"
  tm_scope: source.bsl
  ace_mode: text
  language_id: 0
2-Dimensional Array:
  type: data
  color: "#38761D"
  extensions:
  - ".2da"
  tm_scope: source.2da
  ace_mode: text
  language_id: 387204628
4D:
  type: programming
  color: "#004289"
  extensions:
  - ".4dm"
  tm_scope: source.4dm
  ace_mode: text
  language_id: 577529595
ABAP:
  type: programming
  color: "#E8274B"
  extensions:
  - ".abap"
  tm_scope: source.abap
  ace_mode: abap
  language_id: 1
ABAP CDS:
  type: programming
  color: "#555e25"
  extensions:
  - ".asddls"
  tm_scope: source.abapcds
  language_id: 452681853
  ace_mode: text
ABNF:
  type: data
  ace_mode: text
  extensions:
  - ".abnf"
  tm_scope: source.abnf
  language_id: 429
AGS Script:
  type: programming
  color: "#B9D9FF"
  aliases:
  - ags
  extensions:
  - ".asc"
  - ".ash"
  tm_scope: source.c++
  ace_mode: c_cpp
  codemirror_mode: clike
  codemirror_mime_type: text/x-c++src
  language_id: 2
AIDL:
  type: programming
  color: "#34EB6B"
  tm_scope: source.aidl
  extensions:
  - ".aidl"
  ace_mode: text
  interpreters:
  - aidl
  language_id: 451700185
AL:
  type: programming
  color: "#3AA2B5"
  extensions:
  - ".al"
  tm_scope: source.al
  ace_mode: text
  language_id: 658971832
AMPL:
  type: programming
  color: "#E6EFBB"
  extensions:
  - ".ampl"
  - ".mod"
  tm_scope: source.ampl
  ace_mode: text
  language_id: 3
ANTLR:
  type: programming
  color: "#9DC3FF"
  extensions:
  - ".g4"
  tm_scope: source.antlr
  ace_mode: text
  language_id: 4
API Blueprint:
  type: markup
  color: "#2ACCA8"
  ace_mode: markdown
  extensions:
  - ".apib"
  tm_scope: text.html.markdown.source.gfm.apib
  language_id: 5
APL:
  type: programming
  color: "#5A8164"
  extensions:
  - ".apl"
  - ".dyalog"
  interpreters:
  - apl
  - aplx
  - dyalog
  tm_scope: source.apl
  ace_mode: text
  codemirror_mode: apl
  codemirror_mime_type: text/apl
  language_id: 6
ASL:
  type: programming
  ace_mode: text
  extensions:
  - ".asl"
  - ".dsl"
  tm_scope: source.asl
  language_id: 124996147
ASN.1:
  type: data
  extensions:
  - ".asn"
  - ".asn1"
  tm_scope: source.asn
  ace_mode: text
  codemirror_mode: asn.1
  codemirror_mime_type: text/x-ttcn-asn
  language_id: 7
ASP.NET:
  type: programming
  tm_scope: text.html.asp
  color: "#9400ff"
  aliases:
  - aspx
  - aspx-vb
  extensions:
  - ".asax"
  - ".ascx"
  - ".ashx"
  - ".asmx"
  - ".aspx"
  - ".axd"
  ace_mode: text
  codemirror_mode: htmlembedded
  codemirror_mime_type: application/x-aspx
  language_id: 564186416
ATS:
  type: programming
  color: "#1ac620"
  aliases:
  - ats2
  extensions:
  - ".dats"
  - ".hats"
  - ".sats"
  tm_scope: source.ats
  ace_mode: ocaml
  language_id: 9


require 'yaml'

module Linguist
  module Strategy

    # Detects language based on extension
    class Extension
      # Public: Use the file extension to detect the blob's language.
      #
      # blob               - An object that quacks like a blob.
      # candidates         - A list of candidate languages.
      #
      # Examples
      #
      #   Extension.call(FileBlob.new("path/to/file"))
      #
      # Returns an array of languages associated with a blob's file extension.
      # Selected languages must be in the candidate list, except if it's empty,
      # in which case any language is a valid candidate.
      def self.call(blob, candidates)
        return candidates if generic? blob.name.to_s
        languages = Language.find_by_extension(blob.name.to_s)
        candidates.any? ? candidates & languages : languages
      end

      # Public: Return true if filename uses a generic extension.
      def self.generic?(filename)
        self.load
        @generic.any? { |ext| filename.downcase.end_with? ext }
      end

      @generic = []

      # Internal: Load the contents of `generic.yml`
      def self.load()
        return if @generic.any?
        data = YAML.load_file(File.expand_path("../../generic.yml", __FILE__))
        @generic = data['extensions']
      end
    end
  end
end


```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NOBUOOURA/euler.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

# Header 1
## Header 2
### Header 3

# Mac
.DS_Store
.AppleDouble
.LSOverride
 
# Icon must end with two \r
Icon
 
# Thumbnails
._*
 
# Files that might appear on external disk
.Spotlight-V100
.Trashes
 
# Directories potentially created on remote AFP share
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

# Windows thumbnail cache files
Thumbs.db
ehthumbs.db
ehthumbs_vista.db

# Dump file
*.stackdump

# Folder config file
[Dd]esktop.ini

# Recycle Bin used on file shares
$RECYCLE.BIN/

# Windows Installer files
*.cab
*.msi
*.msm
*.msp

# Windows shortcuts
*.lnk

# PyCharm
.idea/

# Jupyter Notebook
# *.ipynb
.ipynb_checkpoints/

# Windows default autosave extension
*.asv

# OSX / *nix default autosave extension
*.m~

# Compiled MEX binaries (all platforms)
*.mex*

# Packaged app and toolbox files 
*.mlappinstall 
*.mltbx 
  
# Generated helpsearch folders 
helpsearch*/ 

# Simulink code generation folders
slprj/
sccprj/

# Simulink autosave extension
*.autosave

# Octave session info
octave-workspace

## Core latex/pdflatex auxiliary files:
*.aux
*.lof
*.log
*.lot
*.fls
*.out
*.toc
*.fmt
*.fot
*.cb
*.cb2

## Intermediate documents:
*.dvi
*-converted-to.*
# these rules might exclude image files for figures etc.
# *.ps
# *.eps
# *.pdf

## Generated if empty string is given at "Please type another file name for output:"
.pdf

## Bibliography auxiliary files (bibtex/biblatex/biber):
*.bbl
*.bcf
*.blg
*-blx.aux
*-blx.bib
*.run.xml

## Build tool auxiliary files:
*.fdb_latexmk
*.synctex
*.synctex(busy)
*.synctex.gz
*.synctex.gz(busy)
*.pdfsync

## Auxiliary and intermediate files from other packages:
# algorithms
*.alg
*.loa

# achemso
acs-*.bib

# amsthm
*.thm

# beamer
*.nav
*.pre
*.snm
*.vrb

# changes
*.soc

# cprotect
*.cpt

# elsarticle (documentclass of Elsevier journals)
*.spl

# endnotes
*.ent

# fixme
*.lox

# feynmf/feynmp
*.mf
*.mp
*.t[1-9]
*.t[1-9][0-9]
*.tfm

#(r)(e)ledmac/(r)(e)ledpar
*.end
*.?end
*.[1-9]
*.[1-9][0-9]
*.[1-9][0-9][0-9]
*.[1-9]R
*.[1-9][0-9]R
*.[1-9][0-9][0-9]R
*.eledsec[1-9]
*.eledsec[1-9]R
*.eledsec[1-9][0-9]
*.eledsec[1-9][0-9]R
*.eledsec[1-9][0-9][0-9]
*.eledsec[1-9][0-9][0-9]R

# glossaries
*.acn
*.acr
*.glg
*.glo
*.gls
*.glsdefs

# gnuplottex
*-gnuplottex-*

# gregoriotex
*.gaux
*.gtex

# hyperref
*.brf

# knitr
*-concordance.tex
# TODO Comment the next line if you want to keep your tikz graphics files
*.tikz
*-tikzDictionary

# listings
*.lol

# makeidx
*.idx
*.ilg
*.ind
*.ist

# minitoc
*.maf
*.mlf
*.mlt
*.mtc[0-9]*
*.slf[0-9]*
*.slt[0-9]*
*.stc[0-9]*

# minted
_minted*
*.pyg

# morewrites
*.mw

# nomencl
*.nlo

# pax
*.pax

# pdfpcnotes
*.pdfpc

# sagetex
*.sagetex.sage
*.sagetex.py
*.sagetex.scmd

# scrwfile
*.wrt

# sympy
*.sout
*.sympy
sympy-plots-for-*.tex/

# pdfcomment
*.upa
*.upb

# pythontex
*.pytxcode
pythontex-files-*/

# thmtools
*.loe

# TikZ & PGF
*.dpth
*.md5
*.auxlock

# todonotes
*.tdo

# easy-todo
*.lod

# xindy
*.xdy

# xypic precompiled matrices
*.xyc

# endfloat
*.ttt
*.fff

# Latexian
TSWLatexianTemp*

## Editors:
# WinEdt
*.bak
*.sav

# Texpad
.texpadtmp/

# Kile
*.backup

# KBibTeX
*~[0-9]*

# auto folder when using emacs and auctex
/auto/*

# expex forward references with \gathertags
*-tags.tex

# Visual Studio Code
.vscode/

# graphics
*.png

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

```


