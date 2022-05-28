# Linux i686: development platform for [PlatformIO](https://platformio.org)

Linux i686 (32-bit) is a Unix-like and mostly POSIX-compliant computer operating system (OS) assembled under the model of free and open-source software development and distribution. Using host OS (Mac OS X or Linux 32-bit) you can build native application for Linux i686 platform.

* [Home](https://registry.platformio.org/platforms/platformio/linux_i686) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/linux_i686.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = linux_i686
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-linux_i686.git
board = ...
...
```

# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/linux_i686.html).
