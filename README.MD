## TurnKey Linux Automated Builds

Welcome to TKLBuildReports! The appliances are automatically built every Monday at ~12PM UTC. This repository is updated with download links and potentially reports for these builds as well.

These are reports and download links for builds on my own custom appliances.

Note: If you do not see any build reports for the most recent build, it's most likely because nothing changed since the last build of these appliances.

## About These Builds

These builds are customized by me. All builds include a built in firewall (ufw), custom installation and setup, and in gnusocial's case custom plugins (Qvitter, 2FA, and rabbitmq).

These builds use all original source code from the original developer, which is all included in the build iso.


### ntopng

This appliance is built from source so please refer to https://github.com/ntop/ntopng for reporting bugs.

### GNUSocial

This appliance is a PHP script, technically built from source (although you don't compile php). It includes Qvitter, a 2FA plugin, and rabbitmq to help with resource management.

### NextCloud

Standard install of nextcloud. Nothing really fancy here for now (Planning to include mail client, document editor etc setup for you by default at some point.)



All appliances listed here are built using [TurnKey Linux](http://turnkeylinux.org) with their [TKLDev Appliance](https://www.turnkeylinux.org/tkldev) as well as their [TKLCore Appliance](https://www.turnkeylinux.org/core).
