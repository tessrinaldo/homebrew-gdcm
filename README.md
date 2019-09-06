# Homebrew formula for GDCM with command line tools
Grassroots DICOM (`GDCM`) is an implementation of the DICOM standard designed to be open source so that researchers may access clinical data directly. Unfortunately, the current `Homebrew/core` package for `GDCM` installs without the functionality 
of command line tools such as `gdcmconv`, `gdcmanon`, `gdcmdiff`, and others. This is a modified 
Homebrew formula that enables the use of command line tools by setting 
`DGDCM_BUILD_APPLICATIONS=ON` when `cmake` compiles. To 
install, simply run:

`brew install tessrinaldo/homebrew-gdcm/gdcm-with-tool`

Or, equivalently:

`brew tap tessrinaldo/homebrew-gdcm`

`brew install gdcm-with-tool`

Note that this install is for `GDCM version 3.0.1`.

**9/6/2019: My PR to get this changed merged into homebrew/core has been approved!** So `brew install gdcm` now has this feature, rendering my tap obsolete.

