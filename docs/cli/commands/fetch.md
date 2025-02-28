# fetch

Fetches resources from configured providers.

This requires a config.hcl file which can be generated by `cloudquery init`.

## Usage:
```bash
cloudquery fetch [flags]

Examples:
  # Fetch configured providers to PostgreSQL as configured in config.hcl
  cloudquery fetch

Flags:
  -d, --disable-delete        disable pre-fetch fetch delete
      --fail-on-error         CloudQuery should return a failure error code if provider has any error
  -h, --help                  help for fetch
      --skip-schema-upgrade   skip schema upgrade of provider fetch, disabling this flag might cause issues
```

## Additional Help Topics:
```
Use "cloudquery fetch options" for a list of global CLI options.
```
