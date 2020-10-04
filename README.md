# GitHub Actions + Haxelib Publish

This is a GitHub Actions Workflow demonstration that automatically creates a GitHub Release, and publishes your Haxe library to [haxelib](https://lib.haxe.org/) whenever your version on `haxelib.json` file changes.

See the [workflow implementation here](.github/workflows/release-and-publish.yml)

## Secrets

You will need to provide your haxelib password as a secret on GitHub (Settings > Secrets -> New Secret)

- `HAXELIB_PASSWORD`: Your haxelib password

## License

MIT