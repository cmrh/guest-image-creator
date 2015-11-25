# guest-image-creator
Guest image creator

This is a script forked from:

https://jboggs.fedorapeople.org/guest-image-ovf-creator.py

The same script is included in Red Hat's `rhel-guest-image` source package and
is used to generate simple OVF metadata for a qcow2 image.

The generic metadata consists of a limited CPU, memory, etc. that is enough
for importing the resulting OVF in RHEV-M's export domain.

Launch it with "--help" for instructions.
