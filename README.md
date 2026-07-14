# setup-zig

This action sets up a Zig environment for use in Github Actions:
 - Install zigup for Linux and Mac OS systems (x86_64, aarch64)

## Usage
See [action.yml](action.yml)

```yaml
- uses: drflamemontgomery/setup-zig@v0.1.1-alpha
  with:
    version: 0.16.0
    os: linux
    arch: x86_64
```

Supported versions include any valid [anyzig](https://github.com/marler8997/anyzig) version specifier

## License

This project is released under the [MIT License](LICENSE)
