# Net::ZVT

Net::ZVT is a Perl module that provides communication with electronic cash terminals based on the ZVT protocol.


# ZVT reference

The full documentation of the ZVT protocol can be downloaded [here](http://www.zvt-kassenschnittstelle.de/).

Sample from documentation @ page 137 version 13.07.

Design recommendation:

    lib
    |- Net/
    |   \- ZVT
    |       |- Handles
    |       |   |- Authorization
    |       |   \- Confirmation
    |       |- Card_IDs
    |       |- DefinedDataObjects 
    |       |- Commands
    |           \- Bitmaps
    |       |- Exceptions/ErrorMessages
    |       \- Terminal
    |           |- Driver
    |           \- StatusCodes
    |
    \- Test
        \- Net
            \- ZVT



## LICENSE AND COPYRIGHT

Copyright (C) 2017 Dominic Sonntag.

This program is free software; you can redistribute it and/or modify it
under the terms of the the Artistic License (2.0). You may obtain a
copy of the full license at:

http://www.perlfoundation.org/artistic_license_2_0