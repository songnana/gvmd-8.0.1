![Greenbone Logo](https://www.greenbone.net/wp-content/uploads/gb_logo_resilience_horizontal.png)

# Greenbone Vulnerability Manager

[![GitHub releases](https://img.shields.io/github/release/greenbone/gvmd.svg)](https://github.com/greenbone/gvmd/releases)
[![Code Documentation Coverage](https://img.shields.io/codecov/c/github/greenbone/gvmd.svg?label=Doc%20Coverage&logo=codecov)](https://codecov.io/gh/greenbone/gvmd)
[![CircleCI](https://circleci.com/gh/greenbone/gvmd/tree/master.svg?style=svg)](https://circleci.com/gh/greenbone/gvmd/tree/master)

The Greenbone Vulnerability Manager is the central management service between
security scanners and the user clients.

It manages the storage of any vulnerability management configurations and of the
scan results. Access to data, control commands and workflows is offered via the
XML-based Greenbone Management Protocol (GMP). The primary scanner
*[OpenVAS Scanner](https://github.com/greenbone/openvas-scanner)*
is controlled directly via protocol OTP while any other remote scanner is coupled
with the Open Scanner Protocol (OSP).

## Installation and Usage

This module can be configured, built and installed with following commands:

```sh
cmake .
make install
```

For detailed installation requirements and instructions, please see the file
[INSTALL.md](INSTALL.md). The file also contains instructions for setting up
`gvmd` and for connecting `gvmd` to vulnerability scanners and to the *GSA* web
interface.

In case everything was installed using the defaults, then starting the manager
daemon can be done with this simple command:

```sh
gvmd
```

To see all available command line options of gvmd enter this command:

```sh
gvmd --help
```

If you are not familiar or comfortable building from source code, we recommend
that you use the Greenbone Community Edition, a prepared virtual machine with a
readily available setup. Information regarding the virtual machine is available
at <https://www.greenbone.net/en/community-edition/>.

## Support

For any question on the usage of `gvmd` please use the [Greenbone Community
Portal](https://community.greenbone.net/c/gse). If you found a problem with the
software, please [create an issue](https://github.com/greenbone/gvmd/issues) on
GitHub. If you are a Greenbone customer you may alternatively or additionally
forward your issue to the Greenbone Support Portal.

## Maintainer

This project is maintained by [Greenbone Networks GmbH](https://www.greenbone.net/).

## Contributing

Your contributions are highly appreciated. Please [create a pull
request](https://github.com/greenbone/gvmd/pulls) on GitHub. Bigger changes need
to be discussed with the development team via the [issues section at
GitHub](https://github.com/greenbone/gvmd/issues) first.

## License

Copyright (C) 2009-2018 [Greenbone Networks GmbH](https://www.greenbone.net/)

Licensed under the [GNU General Public License v2.0 or later](COPYING).

#gvmd-8.0.1
#与官网版本一致
#用于自己研究gvmd的代码，修改代码便于版本控制
