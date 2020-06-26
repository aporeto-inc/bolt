# BoltDB

This is a fork of https://github.com/boltdb/bolt .

However, this has been adjusted to use `github.com/aporeto-inc/bolt` as the golang import everywhere.
It is also being declared as a module.
This is necessary so that we can treat this code as an independent package from the "real" bolt implementation.

**NOTE:** The sole use-case for this is to support special file access in the `containermetadata` package of the enforcer for containerd. You most likely do not want to use this fork for anything else!
