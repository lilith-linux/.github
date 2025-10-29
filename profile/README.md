# Lilith OS

> **⚠️ Currently under active development** - Not yet ready for production use

A minimal, modern Linux distribution built for ultimate customization.

## Philosophy

Lilith Linux strips away the unnecessary to give you complete control. Built on musl libc, every component is chosen for simplicity, security, and performance.

## Core Features

- **musl libc** - Lightweight, fast, and standards-compliant
- **hclos package manager** - Minimal overhead, maximum control
- **Source-first approach** - Build everything to your specifications
- **Rolling release** - Always current, never obsolete
- **Minimal base system** - Start with nothing, add only what you need

## Getting Started

*ISO releases coming soon*

Once available, download the ISO and boot from USB or virtual machine.

```bash
# After installation, manage packages with hclos
hclos install <package>

# Search available packages
hclos search <query>

# Update system
hclos update && hclos upgrade
```

## Why Lilith?

**Minimal by design** - No bloat, no unnecessary services, no assumptions about your use case.

**Modern tooling** - Latest kernel, contemporary build systems, up-to-date packages.

**musl advantage** - Smaller binaries, faster startup, cleaner codebase than glibc alternatives.

**Ultimate flexibility** - From embedded systems to desktop workstations, build what you need.

## System Requirements

- x86_64 architecture
- 256MB RAM minimum (512MB recommended)
- 2GB disk space for base system

## Documentation

Documentation and website are currently being prepared and will be available at a later date.

## Community

Community channels will be announced once the project reaches beta stage.

## Contributing

Interested in contributing? Feel free to open issues or reach out. Contribution guidelines will be formalized as the project matures.

## License

Lilith OS is primarily released under the BSD-3-Clause License. Individual packages retain their original licenses.

---

*"Minimal. Modern. Yours."*
