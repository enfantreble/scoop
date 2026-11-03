## Personal Scoop bucket.

It exists primarily for software that I use but cannot conveniently install from an existing Scoop bucket, including:

* Applications for which no suitable Scoop manifest exists.
* Commercial or proprietary software for which I own a valid license.
* Software where my license entitles me to a specific version or a maximum version rather than the latest release.
* Older versions that must intentionally remain pinned to their last usable free version - subsequent versions made the free unusable.
* Software whose original vendor download URL has disappeared or is no longer suitable for automated installation.
* Personal tools or unusual packages that are useful to me but inappropriate for submission to a public

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add enfantreble https://github.com/enfantreble/scoop
scoop install enfantreble/<manifestname>
```
