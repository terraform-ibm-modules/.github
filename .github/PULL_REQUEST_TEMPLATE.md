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
Identify the type of release. For information about the changes in a semantic versioning release, see [Release versioning](https://terraform-ibm-modules.github.io/documentation/#/versioning).

- [ ] No release
- [ ] Patch release (`x.x.X`)
- [ ] Minor release (`x.X.x`)
- [ ] Major release (`X.x.x`)

##### Release notes content

If a release is required, replace this text with information that users need to know about the release. Write the release notes to help users understand the changes, and include information about how to update from the previous version.

Your notes help the merger write the commit message for the PR that is published in the release notes for the module.

### Run the pipeline

If the CI pipeline doesn't run when you create the PR, the module requires a user with GitHub collaborators access to run the pipeline.

You run the CI pipeline when the PR is ready for review and you expect tests to pass. Add a comment to the PR with the following text:

```
/run pipeline
```

### Checklist for reviewers

- [ ] If relevant, a test for the change is included or updated with this PR.
- [ ] If relevant, documentation for the change is included or updated with this PR.

### Merge actions for mergers

- Use a relevant [conventional commit](https://www.conventionalcommits.org/) message that is based on the PR contents and any release notes provided by the PR author. The commit message determines whether a new version of the module is needed, and if so, which semver increment to use (major, minor, or patch).
- Merge by using "Squash and merge".
