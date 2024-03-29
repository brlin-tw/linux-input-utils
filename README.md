# Linux input device management utilites

Manage Linux input devices(mice, keyboards, touch pads, and more) with ease!

<https://gitlab.com/brlin/linux-input-utils>  
[![The GitLab CI pipeline status badge of the project's `main` branch](https://gitlab.com/brlin/linux-input-utils/badges/main/pipeline.svg?ignore_skipped=true "Click here to check out the comprehensive status of the GitLab CI pipelines")](https://gitlab.com/brlin/linux-input-utils/-/pipelines) [![GitHub Actions workflow status badge](https://github.com/brlin-tw/linux-input-utils/actions/workflows/check-potential-problems.yml/badge.svg "GitHub Actions workflow status")](https://github.com/brlin-tw/linux-input-utils/actions/workflows/check-potential-problems.yml) [![pre-commit enabled badge](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "This project uses pre-commit to check potential problems")](https://pre-commit.com/) [![REUSE Specification compliance badge](https://api.reuse.software/badge/gitlab.com/brlin/linux-input-utils "This project complies to the REUSE specification to decrease software licensing costs")](https://api.reuse.software/info/gitlab.com/brlin/linux-input-utils)

## Features

This application currently features the following utilities:

* [Utility to enumerate existing Linux input devices and their display names](bin/enumerate-input-devices)
* [Utility to disable specified Linux input devices using their identifier number](bin/disable-input-devices)
* [Utiltiy to re-enable disabled Linux input devices](bin/enable-input-devices)

## Installation

Currently no installation method is implemented, you'll have to:

1. Download the release archive from [the Releases page](https://gitlab.com/brlin/linux-input-utils/-/releases).
1. Extract the downloaded release archive.
1. Add the path of the [bin](bin) directory in the release archive to your command search PATHs.

These inconveniences may be dealt with in the future releases.

## Licensing

Unless otherwise noted(individual file's header/[REUSE DEP5](.reuse/dep5)), this product is licensed under [the 3.0 version of the GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), or any of its recent versions you would prefer.

This work complies to [the REUSE Specification](https://reuse.software/spec/), refer the [REUSE - Make licensing easy for everyone](https://reuse.software/) website for info regarding the licensing of this product.
