# GitHub Actions + Haxelib Publish (test repo)

> Not working yet.

How the process to automatically publish to [haxelib](https://lib.haxe.org/) works:

- Build the project (not implemented here)
- Perform the following if `"version"` has changed on `haxelib.json`
  - Create a Release on GitHub with version number used on the `haxelib.json`
  - Publish the package using `haxelib`

See the [workflow implementation here](.github/workflows/release-and-publish.yml)


## License

MIT