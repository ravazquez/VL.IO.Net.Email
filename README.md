# VL.Net.IO.Email
A [VL](https://vvvv.org/documentation/vl) set of nodes to do basic email tasks. Included nodes are SendEmail, SendEmail (Spread) and ListEmails. The nodes can also be used in vvvv.

Both SendEmail nodes use the standard System.Net API and support only SMTP.

ListEmails uses [MailKit and MimeKit](http://www.mimekit.net/) and currently supports only POP3.

ListEmails assumes all attachments are image attachments and tries to parse their content as such.

## Using the library
Go to vvvv gamma's quad menu/manage nugets/command-line and type

```
nuget install VL.IO.Net.Email
```

Open the help browser (<kbd>F1</kbd>) and look for Email, you'll find two basic help patches showing how to use the nodeset.

vvvv beta help patches can be found here:

    X:\libs.VL\VL.Net.IO.Email\vvvv\girlpower\

### Cloning the repository
If you want to contribute to this repository, clone it into a directory like:
 
    X:\vl-libs\VL.Net.IO.Email

### Build the C# Project
Open

    X:\vl-libs\VL.Net.IO.Email\src\VL.Net.IO.Email.sln
    
in VisualStudio 2019 and build it. This is necessary for a few things that cannot yet be expressed in vl directly, like enums. 
