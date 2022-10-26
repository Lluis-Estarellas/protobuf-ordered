nanopb directory from https://github.com/nanopb/nanopb
test\test.proto from https://developers.google.com/protocol-buffers/docs/proto

Go to https://developers.google.com/protocol-buffers and https://github.com/nanopb/nanopb to learn how protocol buffers works.
This document only resumes how to create your .proto .pb.c and .pb.h files and store them in an orderly way.

==================IN WINDOWS POWERSHELL==================
Requirements:
· Install python (recommended 3.10)
. pip install scons protobuf grcpio-tools
. pip install python3-protobuf

1.- cd to the directory where this document is.

2.- mkdir dir_name*

3.- New-Item -Path .\dir_name\file_name.proto**

4.- .\dir_name\file_name.proto to edit your .proto file

5.- python .\nanopb\generator\nanopb_generator.py .\dir_name\file_name.proto to generate file_name.pb.c and file_name.pb.h

* name of the directory where you will store your .proto, .pb.c and .pb.h files
** name of your .proto file