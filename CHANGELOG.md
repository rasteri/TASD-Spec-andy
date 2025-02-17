# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), although currently without version numbers added.

## 2023-07-03
### Added
- SNES\_LATCH\_TRAIN to spec

### Removed
- PDF files from `docs/`
- PDF file generation via Makefile

### Fixed
- Correct length for Data of MEMORY\_INIT in spec
- Correct length of Name of MOVIE\_FILE packet in spec


## 2022-09-26
### Added
- TODO.md file
- "Licenses" section in `README.md` file
- "Contributing" section in `README.md` file

### Removed
- "TODO" section in `README.md` file


## 2022-09-26
### Changed
- Rename `docs/draft-tasd-spec-0001/` to `docs/tasd-spec-0001/`

### Fixed
- Use correct path for compiled documents for Makefile contribution rule


## 2022-09-26
### Added
- `latest/` and `tasd-spec-{version}/` directories to `docs/`
- "contribution" rule in `Makefile` to automate the process of adding updated documents to the `docs/` directory
- "Keep a Changelog" link and sentence to this `CHANGELOG.md` file
- Initial `CONTRIBUTING.md` file

### Changed
- Rename `draft-tasd-{version}` to `draft-tasd-spec-{version}`
- Clean up documents rule in `Makefile` to avoid using `cd` and `mv`


## 2022-09-24
### Fixed
- Capitalize "Bigbass" in `README.md`


## 2022-09-24
### Added
- Initial release