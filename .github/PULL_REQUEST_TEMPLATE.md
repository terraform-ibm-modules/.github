### Description

Replace this text with a summary of the changes in this PR. Include why the changes are needed and context about the changes. List required dependencies. If there is a GIT issue for the change, please link it too.

### Types of changes in this PR

#### No release required

- [ ] Examples or tests (addition or updates of examples or tests)
- [ ] Documentation update
- [ ] CI-related update (pipeline, etc.)
- [ ] Other changes that don't affect Terraform code

#### Release required

- [ ] Bug fix (patch release (`x.x.X`): Change that fixes an issue and is compatible with earlier versions)
- [ ] New feature (minor release (`x.X.x`): Change that adds functionality and is compatible with earlier versions)
- [ ] Breaking change (major release (`X.x.x`): Change that is likely incompatible with previous versions)

##### Release notes content

Replace this text with information that users need to know about the bug fixes, features, and breaking changes. This information helps the merger write the commit message that is published in the release notes for the module.

---

### Checklist for reviewers

- [ ] If relevant, a test for the change is included or updated with this PR.
- [ ] If relevant, documentation for the change is included or updated with this PR.

### Merge actions for mergers

- Merge by using "Squash and merge".
- Use a relevant [conventional commit](https://www.conventionalcommits.org/) message that is based on the PR contents and any release notes provided by the PR author.

    The commit message determines whether a new version of the module is needed, and if so, which semver increment to use (major, minor, or patch).
