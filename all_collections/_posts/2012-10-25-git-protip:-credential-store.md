---










<!--more-->
		$ git config credential.helper 'store [options]'

Using this helper will store your passwords unencrypted on disk, protected only by filesystem permissions. If this is not an acceptable security tradeoff there’s always git-credential-cache.

**git-credential-cache**

		$ git config credential.helper 'cache [options]'

This command caches credentials in memory for use by future git programs. The stored credentials never touch the disk, and are forgotten after a configurable timeout. The cache is accessible over a Unix domain socket, restricted to the current user by filesystem permissions.

There you go!