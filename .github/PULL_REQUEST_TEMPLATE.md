### Description

Replace this text with a summary of the changes in this PR. Include why the changes are needed and context about the changes. List required dependencies. If there is a Git issue for the change, please link to it.

### Types of changes in this PR

#### Changes that affect the core Terraform module or submodules
- [ ] Bug fix
- [ ] New feature
- [ ] Dependency update

#### Changes that don't affect the core Terraform module or submodules
- [ ] Examples or tests (addition or updates of examples or tests)
- [ ] Documentation update
- [ ] CI-related update (pipeline, etc.)
- [ ] Other

#### Release required?
See the following [doc](https://terraform-ibm-modules.github.io/documentation/#/versioning) which defines what types of changes should generate what kind of SemVer release, and tick the appropriate box below:

- [ ] No release
- [ ] Patch release (`x.x.X`))
- [ ] Minor release (`x.X.x`))
- [ ] Major release (`X.x.x`)

##### Release notes content

If a release is required, replace this text with information that users need to know about the release. Write the release notes to help users understand the changes, and include information about how to update from the previous version. 

Your notes helps the merger write the commit message for the PR that is published in the release notes for the module.

---

### Checklist for reviewers

- [ ] If relevant, a test for the change is included or updated with this PR.
- [ ] If relevant, documentation for the change is included or updated with this PR.

### Merge actions for mergers

- Use a relevant [conventional commit](https://www.conventionalcommits.org/) message that is based on the PR contents and any release notes provided by the PR author. The commit message determines whether a new version of the module is needed, and if so, which semver increment to use (major, minor, or patch).
- Merge by using "Squash and merge".
