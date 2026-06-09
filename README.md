# soundcloud-audio (maintained fork)

This repository is a maintained fork of `soundcloud-audio.js` that fixes authentication with the SoundCloud API.

I originally created this fork to keep my hobby project, [soundcloud-reverse](https://github.com/alexandre-abrioux/soundcloud-reverse),
working as SoundCloud's authentication flow evolved.
Since the upstream project appears to be inactive, I periodically update this fork to ensure compatibility with the current API.

## Scope

This fork is intentionally minimal:

- ✅ Authentication fixes and maintenance updates
- ✅ Kept compatible with current SoundCloud authentication requirements
- ❌ No new features planned
- ❌ No API changes beyond what is necessary to keep the library working

The goal is simply to keep the library functional and available for existing users.

## Background

The authentication fix implemented in this fork is documented in the original pull request:

<https://github.com/voronianski/soundcloud-audio.js/pull/34>

The upstream repository can be found here:

<https://github.com/voronianski/soundcloud-audio.js>

## Installation

All the fixes are pushed to the [oauth](https://github.com/alexandre-abrioux/soundcloud-audio.js/tree/oauth) branch.
Install the maintained fork directly from GitHub:

```bash
npm install --save https://github.com/alexandre-abrioux/soundcloud-audio.js.git#oauth
```

## Related Project

This fork is primarily maintained to support:

- <https://github.com/alexandre-abrioux/soundcloud-reverse>
