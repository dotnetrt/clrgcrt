# clrgcrt

.NET Core alt garbage collector for realt time applications

Garbage collection or memeory managment in general is a critical and required
part of every real time applications having mixed garbage collected and explicit 
memory managment allocation models. This project aims to provide support
for stop the world event free memeory management for .NET Core applications 
requiring maximum performance or real-time scheduling.

The aim is to be binary compatible drop in replacement for existing .NET Core 
Local GC. Targeted .NET Core framework version is 3.0 or later.

Current status - pre-alpha.

# LICENSE

Code is double licensed: AGPL v3.0 or commercial license.
