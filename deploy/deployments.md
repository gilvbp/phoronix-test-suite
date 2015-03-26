# Pre-Scripted Phoronix Test Suite / Phoromatic Deployments

## deb-package: Generate A Debian/Ubuntu Package

Running `php deploy/deb-package/build-package-deb.php` from the main `phoronix-test-suite/` directory will generate a basic Phoronix-Test-Suite Debian package. This script depends upon `fakeroot` and `dpkg` being present on the system.

## rpm-package: Generate A RedHat/Fedora RPM Package

Running `php deploy/rpm-package/build-package-rpm.php` from the main `phoronix-test-suite/` directory will generate a basic Phoronix-Test-Suite RPM package for Red Hat / Fedora based distributions. This script depends upon `rpmbuild` being present on the system.

## phoromatic-upstart: Reference Upstart job files for Phoromatic

The `*.conf` files provide basic `phoromatic-client` and `phoromatic-server` job files for Upstart-powered Linux systems looking to deploy the Phoromatic on either the front or back-end. Read the Phoronix Test Suite documentation for more details.

## phoromatic-systemd: Reference systemd service files for Phoromatic

The `*.service` files provide basic `phoromatic-client` and `phoromatic-server` job files for systemd-based Linux systems looking to deploy Phoromatic for controlling the Phoronix Test Suite.