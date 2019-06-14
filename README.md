# VL.Net.Email
A [VL](https://vvvv.org/documentation/vl) set of nodes to do basic email tasks. Included nodes are SendEmail, SendEmail (Spread) and ListEmails. The nodes can also be used in vvvv.

Both SendEmail nodes use the standard System.Net API and support only SMTP.

ListEmails uses [MailKit and MimeKit](http://www.mimekit.net/) and currently supports only POP3.

## Using the library
In order to use this library with vl you have to clone this repository and build the Visual Studio 21017 solution as described below.

After building you can just reference X:\libs.VL\VL.Net.Email\VL.Net.Email.vl in your VL document and use the nodes.

vvvv demo patches can be found here:

    "X:\libs.VL\VL.Net.Email\vvvv\girlpower\"

## Cloning the repository
If you want to contribute to this repository, clone it into a directory like:
 
    X:\vl-libs\VL.Net.Email

### Build the C# Project
Open

    X:\vl-libs\VL.Net.Email\src\VL.Net.Email.sln
    
in VisualStudio 2017 and build it. This is necessary for a few things that cannot yet be expressed in vl directly, like enums. 