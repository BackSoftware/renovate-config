# renovate-config

Configuration for [Renovate](https://renovateapp.com/).

## Usage

### Non-JavaScript Projects (or JavsScript with separate `renovate.json`)

Add `renovate.json` with:

```json
{
  "extends": ["github>backsoftware/renovate-config"]
}
```

### JavaScript Projects

In `package.json`, add:

```json
{
  "renovate": {
    "extends": ["github>backsoftware/renovate-config"]
  }
}
```

## License

All code released under [GNU GPL v3.0][license]

[license]: https://github.com/backsoftware/renovate-config/blob/master/LICENSE
