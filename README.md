# NAME

Catmandu::XLS - modules for working with Excel .xls and .xlsx files

[![Build Status](https://travis-ci.org/LibreCat/Catmandu-XLS.png)](https://travis-ci.org/LibreCat/Catmandu-XLS)
[![Coverage Status](https://coveralls.io/repos/LibreCat/Catmandu-XLS/badge.png?branch=devel)](https://coveralls.io/r/LibreCat/Catmandu-XLS?branch=devel)
[![Kwalitee Score](http://cpants.cpanauthors.org/dist/Catmandu-XLS.png)](http://cpants.cpanauthors.org/dist/Catmandu-XLS)
[![CPAN version](https://badge.fury.io/pl/Catmandu-XLS.png)](http://badge.fury.io/pl/Catmandu-XLS)

# SYNPOSIS

    # Convert Excel to CSV
    $ catmandu convert XLS to CSV < ./t/test.xls > test.csv
    $ catmandu convert XLSX to CSV < ./t/test.xlsx > test.csv

    # Convert Excel to JSON
    $ catmandu convert XLS to JSON
    $ catmandu convert XLS 

    # Convert Excel to JSON providing own field names
    $ catmandu convert XLS --field title,name,isbn

    # Convert Excel to JSON using the column coordinates as field names
    $ catmandu convert XLS --columns 1

    # Convert CSV to Excel
    $ catmandu convert CSV to XLS < test.csv
    $ catmandu convert CSV to XLSX  < test.csv

# MODULES

- [Catmandu::Importer::XLS](https://metacpan.org/pod/Catmandu::Importer::XLS)
- [Catmandu::Importer::XLSX](https://metacpan.org/pod/Catmandu::Importer::XLSX)
- [Catmandu::Exporter::XLS](https://metacpan.org/pod/Catmandu::Exporter::XLS)
- [Catmandu::Exporter::XLSX](https://metacpan.org/pod/Catmandu::Exporter::XLSX)

# AUTHOR

Nicolas Steenlant, `<nicolas.steenlant at ugent.be>`

# CONTRIBUTOR

Vitali Peil, `<vitali.peil at uni-bielefeld.de>`

Johann Rolschewski, `<jorol at cpan.org>`

Patrick Hochstenbach, `<patrick.hochstenbach at ugent.be>`

# COPYRIGHT AND LICENSE

This software is copyright (c) 2013 by Nicolas Steenlant.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
