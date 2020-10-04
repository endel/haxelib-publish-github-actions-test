# GitHub Actions + Haxelib Publish (test repo)

> Not working yet.

How the process to automatically publish to [haxelib](https://lib.haxe.org/) works:

- [Create Release](.github/workflows/create-release.yml): This workflow is going to create a Release tag on GitHub whenever your `"version"` number of `haxelib.json` is changed.
- [Haxelib Publish](.github/workflows/haxelib-publish.yml): This workflow is going to submit your package to haxelib whenever a Release is created on GitHub.


## License

MIT