ERDDAP-SCIENCEBASE PROCESSING
===============================
This repository contains Python files to perform basic tasks associated with retrieving data files and metadata from an ERDDAP server, processing data records, and creating and modifying ScienceBase items. The project attempts to strike a balance between using an ERDDAP server directly and working mainly within a Python environment.


Functions:
-----------
    a) search ERDDAP by category, protocol, keyword         
    b) request / process data using an 'advanced search url'
    c) create / modify ScienceBase records
    d) examine / QC metadata and other information
    e) search for duplicate records by title, filenames, and dataset ID
    f) generate date-time stamped input files and processing uuid for provenance.

  Simple prototyping and tasks are currently constructed


Development Status:
-------------------
Beta 0.3 1/30/2017
Under development, currently testing and refining


Copyright and License:
---------------------
This USGS product is considered to be in the U.S. public domain, and is licensed under
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

Although this software program has been used by the U.S. Geological Survey (USGS), no warranty, expressed or implied,
is made by the USGS or the U.S. Government as to the accuracy and functioning of the program and related program
material nor shall the fact of distribution constitute any such warranty, and no responsibility is assumed by the
USGS in connection therewith.
