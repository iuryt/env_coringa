# Coringa Environment Repository

Welcome to the Coringa repository — a specialized environment tailored for Earth sciences, particularly focusing on oceanographic data analysis. Initially curated for my personal use, the Coringa environment aims to be a central hub offering the most used packages and tools for my different projects. While its genesis was personal, I invite and encourage other enthusiasts and professionals to make use of and benefit from this environment as well.

## Why "Coringa"?
In Portuguese, the term "coringa" signifies a wildcard; an adaptable element able to serve varied purposes. Just as a joker in card games can substitute any other card, becoming one of the most adaptable cards in the deck, the Coringa environment has been designed to be versatile and adaptable.

Our Coringa environment is your "coringa" in the realm of Earth sciences. It encapsulates tools and libraries tailored for the nuanced needs of oceanographic data analysis. Its versatility saves researchers and scientists the hassle of curating distinct environments for each project.

Named "Coringa" to highlight its broad applicability and adaptability, this repository is a tribute to the dynamic nature of Earth sciences, providing a ready-to-deploy environment for various oceanographic and geoscientific projects.

## Setting Up the Environment

First of all, you need to have [mamba installed](https://mamba.readthedocs.io/en/latest/mamba-installation.html#mamba-install).

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/iuryt/env_coringa.git
   cd env_coringa
   ```

2. **Checkout Desired Version (Optional)**:
   If you want a specific version:
   ```bash
   git checkout tags/v0.1.0
   ```
   Replace `0.1.0` with your desired version.

4. **Create the Mamba Environment**:
   ```bash
   mamba env create -f environment.yml -n coringa0.1.0
   ```
   This is going to create a new mamba environment with the name `coringa0.1.0`

## Usage in Projects

When using this environment in a project, reference the specific version used. For example:

"This project uses version 0.1.0 of the Coringa environment. For more details, visit the GitHub repository: https://github.com/iuryt/env_coringa."

Replace `0.1.0` with the used version.

## Contributing and Updating

1. Modify the environment as needed.
2. Update the version number:
   - Increment the major version for significant changes.
   - Increment the minor version for non-breaking changes.
3. Document changes in `CHANGELOG.md`.
5. Commit, tag with the new version, and push to the repository.
```bash
# First, export the current state of your mamba environment to environment.yml
mamba env export -n coringa > environment.yml

# Then, add the updated environment and CHANGELOG.md file to git
git add environment.yml CHANGELOG.md

# Commit with a message indicating the changes
git commit -m "Updated to version <new version> with XYZ changes"

# Tag the commit with the version number
git tag v<new version>

# Push changes and tags to remote repository
git push && git push --tags
```

## Contact

For questions, suggestions, or issues related to the Coringa environment, please [create an issue](https://github.com/iuryt/env_coringa/issues) on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
