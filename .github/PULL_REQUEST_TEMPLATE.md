### Description

<!--- Replace this text with a summary of the changes in this PR. Include why the changes are needed and context about the changes. List required dependencies. If there is a Git issue for the change, please link to it. --->

### Release required?
<!--- Identify the type of release. For information about the changes in a semantic versioning release, see [Release versioning](https://terraform-ibm-modules.github.io/documentation/#/versioning). --->

- [ ] No release
- [ ] Patch release (`x.x.X`)
- [ ] Minor release (`x.X.x`)
- [ ] Major release (`X.x.x`)

##### Release notes content

<!--- If a release is required, replace this text with information that users need to know about the release. Write the release notes to help users understand the changes, and include information about how to update from the previous version.

Your notes help the merger write the commit message for the PR that is published in the release notes for the module. --->

### Run the pipeline

If the CI pipeline doesn't run when you create the PR, the PR requires a user with GitHub collaborators access to run the pipeline.

Run the CI pipeline when the PR is ready for review and you expect tests to pass. Add a comment to the PR with the following text:

```
/run pipeline
```

### Checklist for reviewers

- [ ] If relevant, a test for the change is included or updated with this PR.
- [ ] If relevant, documentation for the change is included or updated with this PR.

### For mergers

- Use a conventional commit message to set the release level. Follow the [guidelines](https://terraform-ibm-modules.github.io/documentation/#/merging.md).
- Include information that users need to know about the PR in the commit message. The commit message becomes part of the GitHub release notes.
- Use the **Squash and merge** option.
