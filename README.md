# lambda-ghostscript

This repository contains a compiled version of Ghostscript which works with Amazon Web Services(AWS) Lambda.

These binaries are based on Ghostscript 9.20.

AWS Lambda is using old version of Ghostscript which causes many issues, since Lambda has the ability to use local libraries which can be packed inside the function archive, this repository can save you some time.

You can include the files inside your project and use a Ghostscript Node js package to use it.
