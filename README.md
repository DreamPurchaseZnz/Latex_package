# Latex
## Spacing between the items 
```
\begin{itemize}
  \setlength\itemsep{1em}
  \item one
  \item two
  \item three
\end{itemize}
```


## parbox and minipage
A parbox is a box whose contents are created in paragraph mode

```
\parbox[position][height][inner-pos]{width}{text}              
```
For larger pieces of text, including ones containing a paragraph-making environment, you should use a minipage environment
```
\begin{minipage}[position]{width}        
  text
 \end{minipage}
```
Footnotes in a minipage environment are handled in a way that is particularly useful for putting footnotes in figures or tables.

## New command
```
\newcommand{\suma}{\Large$+$}
```

## Math operation
```
multline
align
gather
```
---------------------------------------------basic-------------------------------------------------------------------------------------
# Latex2e Help
[help](http://herbert.the-little-red-haired-girl.org/html/latex2e/Top.html)
```
Overview What is LaTeX?
Commands                                 # Commands within a LaTeX document.
Parameters                               # The command line.
Command Index                            # An alphabetical list of LaTeX commands.
Concept Index                            # An alphabetical list of concepts.
```

## overview of latex and local guide

The LaTeX command typesets a file of text using the TeX program and the LaTeX Macro package for TeX

- A "Device Independent", or '.dvi' file: for device command translation
- A "transcript" or "log" file: contain summary information and diagnostic messages for any errors discovered in the input file
- An "auxiliary" or "aux" file: this is used by Latex itself, for things such as sectioning

## command

A latex command begins with the command name, which consists of a "\" followed by either
- a string of letters
- a single non-letter

Arguments  contained in square brackets \[\], are optional while arguments contained in braces \{\} are required

Note: Latex is case sensitive.
```
Counters                    # Internal counters used by LaTeX
Cross References            # Automatic referencing
Definitions                 # Define your own commands etc
Document Classes            # Some of the various classes available
Environments                # Such as enumerate & itemize
Footnotes                   # How to produce footnotes
Layout                      # Controlling the page layout
Lengths                     # The length commands
Letters                     # The letter class
Line & Page Breaking        # How to insert pagebreaks etc.
Making Paragraphs           # Paragraph commands.
Margin Notes                # Putting remarks in the margin.
Math Formulae               # How to create mathematical formulae.
Modes                       # Paragraph, Math or LR modes.
Page Styles                 # Various styles of page layout.
Sectioning                  # How to section properly.
Spaces & Boxes              # All the associated commands.
Special Characters          # Special reserved characters.
Splitting the Input         # Dealing with big files by splitting.
Starting & Ending           # The formal start & end layouts.
Table of Contents           # How to create a table of contents.
Terminal Input/Output       # User interaction.
Typefaces                   # Such as bold, italics etc.
```
### Counters






## Paremeters

The input file specification indicates the file to be formatted.

TeX uses ".tex" as a default file extension.

You can specify command options by supplying a string as parameters to the command
```
latex  \scrollmode\input foo.tex            # will process "foo.tex" without pausing after every error
```

Output file are always created in the current directory.







