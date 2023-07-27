# Release Process

1. Update the version number in `setup.py`
2. Update `CHANGELOG.md` with the new version number and release date
3. Commit these changes
4. Create a new release on GitHub using the version number as the tag name
5. The GitHub Actions workflow will then publish the new version to PyPI
