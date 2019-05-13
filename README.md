# digitalAssetManagement
This is a set of short python and R programs for managing digital assets. They were designed with specific personal needs in mind but can be expanded and generalized for other use.

A number of these are focused on looking at each file within a particular directory and making a list of what is there as a .txt or CSV file that could be imported into another format

These lists are created in the hope of being able to link derived products to the original items digital objects that they came from. But also to be able to just create a quick list of every single file that is in a partiuclar directory for general data and document management purposes. 

Some are written in python and require some atypical python packages (such as EXIF read from the ianare/exif-py repository) to support the files I'm keeping track of. In that case, the majority are photographs, partiulcarly jpegs, that have metadata in an EXIF format. 

Some programs deal with file conversion. Specifically to convert PDFs into other file formats for processing in different sorts of software. This(eses) are written in R, such as PDF conversions, as those had easily accessible packages for doing that sort of work downloadable through CRAN extensions.

