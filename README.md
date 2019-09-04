# homebrew-gdcm
The current `Homebrew/core` package for `GDCM` installs without the functionality 
of command line tools such as `gdcmconv`, `gdcmanon`, `gdcmdiff`, and others. This is a modified 
Homebrew formula that enables the use of command line tools by setting 
`-DGDCM_BUILD_APPLICATIONS=ON` when `cmake` compiles. To 
install, simply run:

`brew install tessrinaldo/homebrew-gdcm/gdcm-with-tool`

This is equivalent to running:

`brew tap tessrinaldo/homebrew-gdcm`

then

`brew install gdcm-with-tool`

