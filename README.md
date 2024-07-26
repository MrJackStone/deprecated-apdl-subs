# Description

This repo stores all macros from apdl-subs that were deprecated. The intention is to have this repo added to the ANSYS_MACROLIB path so that if any higher level macro calls one of these deprecated subs, ANSYS will throw an error message and abort the run. The error message will be easy to spot in the .err file because it will contain the word DEPRECATED. The user can then rewrite the higher level macro to avoid using a deprecated sub.
