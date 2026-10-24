# App Auto-Patch Configuration Helper

Downloads of **App Auto-Patch Configuration Helper**, a Mac app for admins that builds the
configuration profile for [App Auto-Patch](https://appautopatch.app). Answer one question per
step, or go straight to every setting App Auto-Patch reads; it ends with a summary of what your
users will see, the profiles to deploy, and an optional upload to Jamf Pro.

This repository holds the releases only. Read more on the
[Configuration Helper page](https://appautopatch.app/configuration-helper/).

## Download

Get the [latest release](../../releases/latest):

- `AAPConfigurationHelper-<version>-<build>.pkg` installs **App Auto-Patch Configuration
  Helper** in `/Applications`.
- `AAPConfigurationHelper-<version>-<build>.zip` holds the same app, to drag to Applications
  yourself.

Both are signed with a Developer ID and notarized by Apple. Requires macOS 14 or later, on Apple
Silicon or Intel.

To check a download, put it next to the release's `SHA256SUMS` and run:

```bash
shasum -a 256 -c SHA256SUMS
```

Each release also has a `latest.json` describing it, which the website reads.

## License

[MIT](LICENSE).
