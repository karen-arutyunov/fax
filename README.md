# fax - <SUMMARY>

`fax` is a <SUMMARY-OF-FUNCTIONALITY>.

This file contains setup instructions and other details that are more
appropriate for development rather than consumption. If you want to use
`fax` in your `build2`-based project, then instead see the accompanying
package [`README.md`](<PACKAGE>/README.md) file.

The development setup for `fax` uses the standard `bdep`-based workflow.
For example:

```
git clone .../fax.git
cd fax

bdep init -C @gcc cc config.cxx=g++
bdep update
bdep test
```
