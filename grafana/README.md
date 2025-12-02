# Home Assistant Add-on: Grafana with VictoriaMetrics datasource

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

The open platform for beautiful analytics and monitoring with VictoriaMetrics datasource support.

## About

**This is a fork of the original [Home Assistant Community Add-ons Grafana repository](https://github.com/hassio-addons/addon-grafana) with added VictoriaMetrics datasource plugin support.**

The analytics platform for all your metrics with enhanced VictoriaMetrics integration.

Grafana allows you to query, visualize, alert on and understand your metrics
no matter where they are stored. Create, explore, and share dashboards. Learn
about your Home Automation system using sexy and compelling graphs, and other
data visualizations.

This fork includes the VictoriaMetrics datasource plugin, providing native support for VictoriaMetrics as a data source in Grafana.

Combine this add-on with the InfluxDB add-on to get insanely powerful
insights to your home.

![Grafana in the Home Assistant Frontend][screenshot]


## Fork Information

This repository is a fork maintained independently with the following additions:

- VictoriaMetrics datasource plugin integration

**Note**: Changes made in this fork are not intended to be merged back to the original repository.

## Acknowledgments

**Special thanks to the original authors and contributors of the [Home Assistant Community Add-ons Grafana repository](https://github.com/hassio-addons/addon-grafana).** This fork is based on their excellent work and wouldn't be possible without their contributions to the Home Assistant community.

[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[release-shield]: https://img.shields.io/badge/version-v2.0.0-blue.svg
[release]: https://github.com/ysm-hassio/addon-grafana/tree/v2.0.0
[screenshot]: https://github.com/ysm-hassio/addon-grafana/raw/main/images/screenshot.png