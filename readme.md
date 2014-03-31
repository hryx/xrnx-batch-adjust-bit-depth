Batch Adjust Bit Depth
======================

Description
-----------

This is a Renoise tool (XRNX) that allows you to change the bit depth of all
samples in the currently selected instrument.

Caveats
-------

Currently, Renoise does not expose converting bit depth or sample rate in the
Lua API. So it requires creating a new sample buffer inside Renoise and
copying over the data manually. Therefore, existing samples using
non-standard sample rates are unsupported.

Getting the tool
----------------

Ideally, go to http://www.renoise.com/tools
Or, you can turn the sources into a tool by zipping the files and changing
the file extension to .xrnx.

License
-------

Public Domain
