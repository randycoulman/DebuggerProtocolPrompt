# DebuggerProtocolPrompt

![Maintenance Status](https://img.shields.io/badge/maintenance-active-green.svg)

Prompt for a method protocol when defining a new method in the
debugger.

DebuggerProtocolPrompt is licensed under the MIT license.  See the
Copyright tab in the RB, the 'notice' property of this package, or the
License.txt file on GitHub.

DebuggerProtocolPrompt's primary home is the [Cincom Public Store
Repository](http://www.cincomsmalltalk.com/CincomSmalltalkWiki/Public+Store+Repository).
Check there for the latest version.  It is also on
[GitHub](https://github.com/randycoulman/DebuggerProtocolPrompt).

DebuggerProtocolPrompt was developed in VW 7.9.1, but is compatible
with VW 7.7 and later.  It may also work with earlier versions, but
that has not been tested.  If you find any incompatibilities with VW
7.7 or later, let me know (see below for contact information) or file
an issue on GitHub.

# Introduction

When a MessageNotUnderstood error is raised, the Visualworks debugger
provides the option of defining the missing method.  Normally, the
newly-defined method is placed into the default "As yet unclassified"
method protocol.

DebuggerProtocolPrompt overrides the default behavior, and instead
prompts for a protocol for the new method.

If all of the existing implementers of the new method are in the same
protocol, DebuggerProtocolPrompt automatically places the new method
in that protocol without prompting.

# Usage

Simply load the package and it will be active.

NOTE: It overrides one method in DebuggerService in order to do its
job.

# Acknowledgements

DebuggerProtocolPrompt was originally written by Russel Hill and David
Alford.

# Contributing

I'm happy to receive bug fixes and improvements to this package.  If
you'd like to contribute, please publish your changes as a "branch"
(non-integer) version in the Public Store Repository and contact me as
outlined below to let me know.  I will merge your changes back into
the "trunk" as soon as I can review them.

# Contact Information

If you have any questions about DebuggerProtocolPrompt and how to use
it, feel free to contact me.

* Web site: http://randycoulman.com
* Blog: Courageous Software (http://randycoulman.com/blog)
* E-mail: randy _at_ randycoulman _dot_ com
* Twitter: @randycoulman
* GitHub: randycoulman
