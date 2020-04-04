---
layout: default
title: GPG
---

PGP Key

`Key fingerprint = F535 AEEC C57B C4EE FE62  6871 B19C D619 61B5 B9DA`

The recommended way to get this key is:

`gpg --keyserver hkps://keys.openpgp.org --receive-keys B19CD61961B5B9DA`

It is also available for [download](/steven.malins.asc).

## History

The key contains a separate encryption subkey. The encryption subkey
is rotated every 90days. The current encryption subkey is

`9CCE56F23459CC04`

and it expires 2020-07-01

The key also contains the revoked encryption subkeys. Each subkey has
been revoked **proactively** to create some measure of forward
security. The fact that the subkeys cannot be deleted from the
keyserver is *by design*; it provides an audit trail of changes to the
key. If you are on a system that is starved for space (as in your
counting kilobytes) you can safely delete the revoked subkeys from
your copy; but be warned that if you refresh it from the keyserver you
will get the subkeys back. Again, this is by design because signatures
(revoking a subkey is just adding a revocation signature) cannot, and
should not, be permanently removed from the keyserver.
