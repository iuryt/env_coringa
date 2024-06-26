# Changelog

This file documents all notable changes to env_coringa. The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.1.1] - 2024-06-30

- Downgrade openssl to fix incompatibility bug while creating env.

## [2.1.0] - 2024-06-30

- Adds gee, cmashed, memory_profiler (pip) and updates other packages.

## [2.0.0] - 2024-05-28

- Major changes. Updates and new packages (copernicusmarine, xrft).

## [1.0.0] - 2023-12-11

- Major changes to make it work interactive plotting with Holoviz.

## [0.3.0] - 2023-10-03

- Remove cuda-restricted PyTorch.

## [0.2.0] - 2023-08-22

- Update parcels to 2.4.2.

## [0.1.0] - 2023-08-11

- Initial release.

---

### Guideline to Document Changes:

1. **Versioning**: Use [Semantic Versioning](https://semver.org/). Major.Minor.Patch.
    - `Major`: Introduces breaking changes.
    - `Minor`: Adds new features without breaking backward compatibility.
    - `Patch`: Makes bug fixes or minor changes.

2. **Headings**: 
    - **Added** for new features.
    - **Changed** for changes in existing functionality.
    - **Deprecated** for once-stable features set for removal in upcoming releases.
    - **Removed** for deprecated features removed in this release.
    - **Fixed** for any bug fixes.
    - **Security** in case of vulnerabilities.

3. **Date Format**: Stick to a consistent date format. YYYY-MM-DD is internationally recognized and avoids confusion.

4. **Unreleased**: Changes that are on the main branch but not yet released. Move these to a version number once the release is made.

5. **Be Clear & Concise**: Clearly describe what changed, and if possible, provide context or reasons.
