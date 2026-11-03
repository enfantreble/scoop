# Personal Scoop Bucket

This is my personal Scoop bucket. It is explicitly designed around my own software needs and the commercial licenses I personally own, including the specific version limits imposed by those licenses,including

* Applications for which no suitable Scoop manifest exists.
* Commercial or proprietary software for which I own a valid license.
* Software where my license entitles me to a specific version, or only up to a maximum version, rather than the latest release.
* Older versions that are intentionally pinned to their last usable free version because subsequent releases significantly restricted or removed the functionality of the free version.
* Software whose original vendor download URL has disappeared or is no longer suitable for automated installation.
* Personal tools or unusual packages that are useful to me but are not appropriate for submission to a public Scoop bucket.

## Commercial and Proprietary Software

Some manifests in this bucket may target commercial or proprietary software.

Their inclusion does not grant a license or any additional rights to the software. Installation and use remain subject to the applicable vendor's license terms and Terms of Service, including any restrictions concerning eligible versions.

Users are responsible for possessing any required license or entitlement and for ensuring that their use of the software complies with the applicable license terms and Terms of Service.

## Installation

Add the bucket:

```pwsh
scoop bucket add enfantreble https://github.com/enfantreble/scoop
```

Then install an application:

```pwsh
scoop install enfantreble/<manifestname>
```

### Single app without adding the bucket

A manifest can also be installed directly from its URL:

```pwsh
scoop install https://raw.githubusercontent.com/enfantreble/scoop/master/bucket/<manifestname>.json
```

## Contributions

Pull requests are welcome.

Yeah, I wish...
