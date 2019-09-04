# `brew install gdcm` with command line tools
The current `Homebrew/core` package for `GDCM` installs without the functionality 
of command line tools such as `gdcmconv`, `gdcmanon`, `gdcmdiff`, and others. This is a modified 
Homebrew formula that enables the use of command line tools by setting 
`DGDCM_BUILD_APPLICATIONS=ON` when `cmake` compiles. To 
install, simply run:

`brew install tessrinaldo/homebrew-gdcm/gdcm-with-tool`

Or, equivalently:

`brew tap tessrinaldo/homebrew-gdcm`

`brew install gdcm-with-tool`

Note that this install is for `GDCM version 3.0.1`.

