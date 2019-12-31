# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 1.0.0alpha2 - 2018-02-27

### Added

- Nothing.

### Changed

- [zendframework/zend-expressive-authentication-zendauthentication#5](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/5)
  changes the constructor of the `Mezzio\Authentication\LaminasAuthentication\LaminasAuthentication`
  class to accept a callable `$responseFactory` instead of a
  `Psr\Http\Message\ResponseInterface` response prototype. The
  `$responseFactory` should produce a `ResponseInterface` implementation when
  invoked.

- [zendframework/zend-expressive-authentication-zendauthentication#5](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/5)
  updates the `LaminasAuthenticationFactory` to no longer use
  `Mezzio\Authentication\ResponsePrototypeTrait`, and instead always
  depend on the `Psr\Http\Message\ResponseInterface` service to correctly return
  a PHP callable capable of producing a `ResponseInterface` instance.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.0.0alpha1 - 2018-02-26

### Added

- [zendframework/zend-expressive-authentication-zendauthentication#4](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/4)
  adds support for the 1.0.0alpha3 (and later) release of mezzio-authentication.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- [zendframework/zend-expressive-authentication-zendauthentication#4](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/4)
  drops support for pre-1.0.0alpha3 releases of mezzio-authentication.

- Nothing.

### Fixed

- Nothing.

## 0.3.0 - 2018-02-26

### Added

- [zendframework/zend-expressive-authentication-zendauthentication#3](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/3)
  adds support for the 0.3 release of mezzio-authentication.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- [zendframework/zend-expressive-authentication-zendauthentication#3](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/3)
  removes support for the 0.2 release of mezzio-authentication.

### Fixed

- Nothing.

## 0.2.1 - 2017-12-13

### Added

- [zendframework/zend-expressive-authentication-zendauthentication#1](https://github.com/zendframework/zend-expressive-authentication-zendauthentication/pull/1)
  adds support for the 1.0.0-dev branch of mezzio-authentication.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 0.2.0 - 2017-11-28

### Added

- Adds support for mezzio-authentication 0.2.0.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Adds support for mezzio-authentication 0.1.0.

### Fixed

- Nothing.

## 0.1.0 - 2017-11-09

Initial release.

### Added

- Everything.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.
