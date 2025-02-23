# Azure Blob Remote Volume Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 1.0.2 - 2019-08-08
## Added
- settings fields are now auto suggest fields

## 1.0.1 - 2019-06-07
## Fixed
- guess missing mime/content type

## 1.0.0 - 2019-05-31

Breaking change! To migrate Volumes after upgrading this plugin, edit each Azure Volume and add the required fields from your ENV variables.

### Added
- Store Azure Storage configs on a per-volume basis.
- Allow multiple containers.
- Allow using a container’s subfolder as a Volume.

## 0.1.1 - 2019-05-20
### Fixed
- Fixed Craft 3 Volume requirement of at least a single setting. Thanks [@MarcoWilliamsPF](https://github.com/MarcoWilliamsPF)!

## 0.1.0 - 2019-05-08
### Added
- Initial release
