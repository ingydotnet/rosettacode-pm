RosettaCode
===========

A tool to extract RosettaCode's code samples


# Synopsis

From the command line:

    $ git clone https://github.com/acmeism/RosettaCodeData
    $ cd RosettaCodeData
    $ rosettacode           # or `make build`


# Description

RosettaCode.org is a fantastic wiki that contains ~1200 programming tasks, each
implemented in up to ~900 programming languages.
There are over 100,000 code samples!

This tool aims to make it easier for programmers to obtain and try the various
code samples.

At this point, the main function is to extract the code examples and organize
them into this git repository on GitHub:

* https://github.com/acmeism/RosettaCodeData

The `make build` command in that repository requires this CPAN module, which
does all the work.


# Copyright and License

Copyright 2013-2023 by Ingy döt Net

This program is free software; you can redistribute it and/or modify it under
the same terms as Perl itself.

See http://www.perl.com/perl/misc/Artistic.html
