---
layout: essay
type: essay
published: true
title: The benefits of the Make Utility
date: 2019-01-23
labels:
  - Make Utility
---

# Main Benefits
   The make utility is used to perform an action on multiple files with a one-word command (e.g. "make") or two-word command (e.g. "make example.o").  For example, instead of writing the compiling command and then listing every single file to be compiled one can simply write "make example.o" to create the object file, relieving a lot of time and tedious effort.  The one-word command "make", is a one-word command that the make utility uses and, when evoked, will perform the first command listed in the Makefile.  If there are other commands that need to be executed before the first command then, so long as the commands are entered in the Makefile, the make utility will execute those commands in ascending order.

   In addition, if only one file was changed out of the many needed to create the target file, evoking a make utility command will simply update the single file changed and the target file.  Continuing the compiling example, if only one source code file was changed, out of the many, and "make example.o" was evoked then only the rewritten source code file and the object file will be updated.  This is because the make utility won't compile the source code if the write time of the source code precedes or is the same as the write time of the object code.  This aspect mainly saves time for recompiling hundreds of unedited source code files is unnecessary.

# Other useful aspects
   Another command the make utility supports is the "make clean" command which will remove any files chosen as long as the files are listed on the Makefile under the clean command section.
