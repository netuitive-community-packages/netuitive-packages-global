## Release History

### Version next

* Bugfix to convert to elementTypes array in policy scope
* Adjusted build to use metricly-cli for validation

### Version 1.2.1

* Updated package compatibilities.

### Version 1.2.0

* Removed global defaults for metric settings. Need to keep these out the package until we improve order of precedence.

### Version 1.1.0

* Added global defaults for metric settings.

### Version 1.0.0

* Initial production release of the package for global configurations.  This release contains a single policy, which alerts when less than 50% of the available metrics for an element are being collected.  This policy is disabled by default.