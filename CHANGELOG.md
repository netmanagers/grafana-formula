# Changelog

# [2.0.0](https://github.com/saltstack-formulas/grafana-formula/compare/v1.1.1...v2.0.0) (2019-06-23)


### Features

* **repository:** support rpm-based linux distros ([ded3157](https://github.com/saltstack-formulas/grafana-formula/commit/ded3157))


### BREAKING CHANGES

* **repository:** the parameter `pkg` is now a dictionary. References
 to `grafana.pkg` should be changed to `grafana.pkg.name`.

## [1.1.1](https://github.com/saltstack-formulas/grafana-formula/compare/v1.1.0...v1.1.1) (2019-06-23)


### Bug Fixes

* **macos:** fix service name on macos ([f28d08b](https://github.com/saltstack-formulas/grafana-formula/commit/f28d08b))

# [1.1.0](https://github.com/saltstack-formulas/grafana-formula/compare/v1.0.0...v1.1.0) (2019-06-05)


### Features

* **macos:** basic package and group handling ([bda2a7c](https://github.com/saltstack-formulas/grafana-formula/commit/bda2a7c))

# 1.0.0 (2019-05-06)


### Features

* **grafana-formula:** based on template-formula ([bd466a1](https://github.com/alxwr/grafana-formula/commit/bd466a1))