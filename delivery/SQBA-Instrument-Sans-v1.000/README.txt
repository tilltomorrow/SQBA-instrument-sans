SQBA Instrument Sans, version 1.000
===================================

A custom version of Instrument Sans for SQBA.
Made by Van Lennep Amsterdam, October 2026.


CONTENTS OF THIS FOLDER
-----------------------

fonts/SQBAInstrumentSans-Regular.otf
fonts/SQBAInstrumentSans-Italic.otf
fonts/SQBAInstrumentSans-Bold.otf
fonts/SQBAInstrumentSans-BoldItalic.otf

webfonts/SQBAInstrumentSans-Regular.woff2
webfonts/SQBAInstrumentSans-Italic.woff2
webfonts/SQBAInstrumentSans-Bold.woff2
webfonts/SQBAInstrumentSans-BoldItalic.woff2

SQBA-Instrument-Sans-specimen.pdf   Overview of the typeface and all characters
FONTLOG.txt                         Changes compared to Instrument Sans
OFL.txt                             The license (SIL Open Font License 1.1)


INSTALLING ON MAC
-----------------

1. First remove any older version of SQBA Instrument Sans
   (open Font Book, search for "SQBA", select and choose Remove).
2. Open the fonts folder and select all four files.
3. Double-click them, or drag them into Font Book.
4. Restart any applications that were already open (InDesign, Word, etc.).


INSTALLING ON WINDOWS
---------------------

1. First remove any older version
   (Settings > Personalization > Fonts, search for "SQBA", Uninstall).
2. Open the fonts folder and select all four files.
3. Right-click and choose "Install for all users".
4. Restart any applications that were already open.


USAGE
-----

One family appears in the font menu: SQBA Instrument Sans.
Select it and use the regular buttons or shortcuts for bold and italic:

   Mac:      Cmd+B (bold), Cmd+I (italic)
   Windows:  Ctrl+B (bold), Ctrl+I (italic)

The SQBA letterforms (round dots and accents, the y with a rounded
descender, the angled M, the G without spur, the J with extended
terminal, the Q with alternate tail, the alternate 2, and $ and ¢ with
a solid vertical stroke) are built into the font as the default. There
is nothing to switch on.

The family deliberately comes in one width and two weights. Avoid the
fake bold or fake italic that some applications generate; always choose
the family first and then the style.


USING THE FONTS ON A WEBSITE
----------------------------

The webfonts folder contains the four styles as WOFF2, the format
supported by all current browsers. These files are for the website,
not for installing on your computer (use the OTF files for that).

Upload the files to the server and add the following to the CSS
(adjust the path to where the files are located):

@font-face {
  font-family: "SQBA Instrument Sans";
  src: url("webfonts/SQBAInstrumentSans-Regular.woff2") format("woff2");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: "SQBA Instrument Sans";
  src: url("webfonts/SQBAInstrumentSans-Italic.woff2") format("woff2");
  font-weight: 400;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: "SQBA Instrument Sans";
  src: url("webfonts/SQBAInstrumentSans-Bold.woff2") format("woff2");
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: "SQBA Instrument Sans";
  src: url("webfonts/SQBAInstrumentSans-BoldItalic.woff2") format("woff2");
  font-weight: 700;
  font-style: italic;
  font-display: swap;
}

body { font-family: "SQBA Instrument Sans", sans-serif; }

Use font-weight: 700 for bold and font-style: italic for italic.
Other weights (such as 500 or 600) do not exist in this family; the
browser would generate a fake version of them.


LICENSE
-------

SQBA Instrument Sans is based on Instrument Sans by Rodrigo Fuenzalida
and, like the original, is licensed under the SIL Open Font License 1.1
(see OFL.txt). In short:

- You may use the fonts freely, including commercially, for print,
  documents, presentations, websites and apps.
- You may share the fonts, as long as OFL.txt is included.
- The fonts may not be sold on their own.


QUESTIONS
---------

Van Lennep Amsterdam
www.vanlennep.eu
