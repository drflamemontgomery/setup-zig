# setup-zig

This action sets up a Zig environment for use in Github Actions:
 - Installing zigup for x86_64 linux systems

## Usage
See [action.yml](action.yml)

```yaml
- uses: drflamemontgomery/setup-zig@v0.1.0-alpha
  with:
    version: 0.16.0
```

Supported versions include any valid [anyzig](https://github.com/marler8997/anyzig) version specifier

## License

This project is released under the [MIT License](LICENSE)
