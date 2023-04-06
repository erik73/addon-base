# Home Assistant: Base Image

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[![GitHub Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

[github-sponsors]

Docker base image used by Home Assistant Add-ons.

## About

Features:

- Adds [s6] as a process supervisor.
- Adds `jq` & `curl`, since every add-on uses them.
- Adds Docker [Label Schema][label-schema] support.
- Adds Jemalloc memory allocator.
- Includes a helper library: [Bashio][bashio]
- Includes template helper: [tempio][tempio]
- Handles logs, add-on startup banners and update notifications.
- Several small adjustments and improvements.

## Changelog & Releases

This repository keeps a change log using [GitHub's releases][releases]
functionality.

Releases are based on [Semantic Versioning][semver], and use the format
of `MAJOR.MINOR.PATCH`. In a nutshell, the version will be incremented
based on the following:

- `MAJOR`: Incompatible or major changes.
- `MINOR`: Backwards-compatible new features and enhancements.
- `PATCH`: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You could also [open an issue here][issue] GitHub.

## We have got some Home Assistant add-ons for you

Want some more functionality to your Home Assistant instance?

We have created multiple add-ons for Home Assistant. For a full list, check out
our [GitHub Repository][repository].

## License

MIT License

Copyright (c) 2017-2023 Erik Hilton

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[bashio]: https://github.com/hassio-addons/bashio
[commits-shield]: https://img.shields.io/github/commit-activity/y/erik73/addon-base.svg
[commits]: https://github.com/erik73/addon-base/commits/main
[contributors]: https://github.com/erik73/addon-base/graphs/contributors
[github-actions-shield]: https://github.com/erik73/addon-base/workflows/CI/badge.svg
[github-actions]: https://github.com/erik73/addon-base/actions
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/erik73/addon-base/issues
[label-schema]: http://label-schema.org/
[license-shield]: https://img.shields.io/github/license/erik73/addon-base.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/Project%20Stage-Production%20Ready-brightgreen.svg
[releases-shield]: https://img.shields.io/github/release/erik73/addon-base.svg
[releases]: https://github.com/erik73/addon-base/releases
[repository]: https://github.com/erik73/hassio-addons
[s6]: http://skarnet.org/software/s6/overview.html
[semver]: http://semver.org/spec/v2.0.0.html
[tempio]: https://github.com/home-assistant/tempio
