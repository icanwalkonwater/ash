### Changelog

## [Unreleased] - ReleaseDate

## [0.9.1] - 2022-02-21

### Changed

- Convert `ash` version to a range, allowing [`0.34`](https://github.com/MaikKlein/ash/releases/tag/0.34.0)-[`0.36`](https://github.com/MaikKlein/ash/releases/tag/0.36.0) (#585)

## [0.9.0] - 2021-12-27

### Changed

- Bumped `ash` version to [`0.35`](https://github.com/MaikKlein/ash/releases/tag/0.35.0)

## [0.8.0] - 2021-12-22

### Changed

- Bumped `ash` version to [`0.34`](https://github.com/MaikKlein/ash/releases/tag/0.34.0)

## [0.7.0] - 2021-07-30

### Changed

- Bumped `ash` version to [`0.33`](https://github.com/MaikKlein/ash/releases/tag/0.33.0)

## [0.6.0]

### Changed

- Bumped `ash` version to [`0.32`](https://github.com/MaikKlein/ash/releases/tag/0.32.0)

## [0.5.0]

### Changed
- `impl HasRawWindowHandle` to `dyn HasRawWindowHandle`

## Version 0.4.1

### Changed
- Use `raw-window-metal` to automatically allocate a `CAMetalLayer` if there is none

## Version 0.4.0

### Changed
- Update `ash` version to 0.31

## Version 0.3.0

### Changed
- Update `ash` version to 0.30

## Version 0.2.0

### Changed
- `enumerate_required_extension` renamed to `enumerate_required_extensions`
- `enumerate_required_extensions` will return an error if the window handle is not supported instead of panic.
- `enumerate_required_extensions` may return multiple extension names. Includes all dependent extensions.
- `create_surface` will return an error if the window handle is not supported instead of panic.

## Version 0.1.0
Initial release for `raw-window-handle = "0.3"` with Windows, Linux, Android, MacOS/iOS support.

[Unreleased]: https://github.com/MaikKlein/ash/compare/ash-window-0.9.1...HEAD
[0.9.1]: https://github.com/MaikKlein/ash/releases/tag/ash-window-0.9.1
[0.9.0]: https://github.com/MaikKlein/ash/releases/tag/ash-window-0.9.0
[0.8.0]: https://github.com/MaikKlein/ash/releases/tag/ash-window-0.8.0
[0.7.0]: https://github.com/MaikKlein/ash/releases/tag/ash-window-0.7.0
[0.6.0]: https://github.com/MaikKlein/ash/releases/tag/ash-window-0.6.0
[0.5.0]: https://github.com/MaikKlein/ash/releases/tag/ash-window-0.5.0
