# Brief <a href="#user-content-brief" id="brief">¶</a>

[Shortcut Card](https://app.shortcut.com/rewst/story/4788/crowdstrike-integration)

Write a brief on what this PR does


EXAMPLE: This PR implements and exposes the ability to export an object (and all its dependencies) to a signed, identification-free JSON bundle, and import those bundles to arbitrary orgs in arbitrary envs, avoiding the creation of duplicate objects.

<details>
<summary>Video Demo:</summary>

https://user-images.githubusercontent.com/10016234/211409547-b5a6531d-08f7-47b6-a8ab-627aad0acbc3.mov

</details><br />

## Testing Instructions
Write a list of things to test your changes
- cloning & syncing workflow
- cloning & syncing workflow with subworkflows
- cloning & syncing WF with form trigger
- cloning & syncing WF with template references
- cloning & syncing WF with option generators in forms
- cloning & syncing a cloned workflow
- De-syncing and re-syncing cloned workflows


## Additional Changes
If applicable, write a list of additional refactors or bug fixes
Else, write N/A


## Quick Checklist
Code
- [ ] remove logging
- [ ] remove comments
- [ ] app - memoization and useEffect dependency arrays
- [ ] graph_api - check `migrations/_current.json`
  - [ ] increment revision number
  - [ ] remove personal ref (eg: `"path": "/Users/tim/Documents/GitHub/rewst-app/packages/graph_api/migrations/_current.json",`)
- [ ] graph_api - check mutation resolver has `verifyUserManagesOrg` or other security checks
- [ ] run linting (remove this checkbox when we add pre commit hooks)

Testing
- [ ] unit tests
- [ ] integration tests
- [ ] Playwright tests

Dependencies
- [ ] app
- [ ] graph_api
- [ ] graph_api database migrations
- [ ] engine
- [ ] engine YAML packs, actions, and sensors

---

### PS: Don't forget to add labels