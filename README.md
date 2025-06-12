# ysm Home Assistant add-on repository

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fysm-hassio%2Frepository)

## Add-ons

This repository contains the following add-ons

### &#10003; [Grafana][addon-grafana]

![Latest Version][grafana-version-shield]
![Supports armhf Architecture][grafana-armhf-shield]
![Supports armv7 Architecture][grafana-armv7-shield]
![Supports aarch64 Architecture][grafana-aarch64-shield]
![Supports amd64 Architecture][grafana-amd64-shield]
![Supports i386 Architecture][grafana-i386-shield]

The open platform for beautiful analytics and monitoring

[:books: Grafana add-on documentation][addon-doc-grafana]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Grafana][grafana-issue]


<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[addon-grafana]: https://github.com/ysm-hassio/addon-grafana/tree/v11.0.0
[addon-doc-grafana]: https://github.com/ysm-hassio/addon-grafana/blob/v11.0.0/README.md
[grafana-issue]: https://github.com/ysm-hassio/addon-grafana/issues
[grafana-version-shield]: https://img.shields.io/badge/version-v11.0.0-blue.svg
[grafana-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[grafana-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[grafana-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[grafana-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[grafana-i386-shield]: https://img.shields.io/badge/i386-no-red.svg

[semver]: http://semver.org/spec/v2.0.0.html
