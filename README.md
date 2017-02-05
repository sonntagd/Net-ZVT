# Net::ZVT

Net::ZVT is a Perl module that provides communication with electronic cash terminals based on the ZVT protocol.


# ZVT reference

The full documentation of the ZVT protocol can be downloaded [here](http://www.zvt-kassenschnittstelle.de/).

Sample from documentation @ page 137 version 13.07.

Design recommondation:

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