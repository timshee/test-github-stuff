# BUG
[Shortcut Card](https://app.shortcut.com/rewst/story/4788/crowdstrike-integration)

# Brief <a href="#user-content-brief" id="brief">¶</a>

Write a brief on the situation

EXAMPLE: User described only recieving 100 elements from their List Users Duo Action.

<details>

<summary>Bug</summary>

*Currently:*
<img width="1462" alt="Screen Shot 2023-01-10 at 11 39 09 AM" src="https://user-images.githubusercontent.com/10016234/211610007-a3f5f060-32a0-4f9a-a599-b2b57e4a29f0.png">


*Fixed:*
<img width="1462" alt="Screen Shot 2023-01-10 at 11 32 05 AM" src="https://user-images.githubusercontent.com/10016234/211608278-2145105e-5315-4594-b957-0d79cf386363.png">

</details><br />

# Solution
Write a brief on the solution's changes

EXAMPLE:

PROBLEM: action was missing `paginate` and not reading pagination from correct variable (was reading from `**kwargs` when it was already specified.

SOLUTION
- add pagination
- fix issues with Action's returned status by using `RestAPIRequestBaseAction`'s `get_action_status`


---
PS: Don't forget to add labels

---
# FEATURE 

# Brief <a href="#user-content-brief" id="brief">¶</a>

[Shortcut Card](https://app.shortcut.com/rewst/story/4788/crowdstrike-integration)

Write a brief on what this PR does

<details open>
<summary>Video Demo:</summary>

https://user-images.githubusercontent.com/10016234/211409547-b5a6531d-08f7-47b6-a8ab-627aad0acbc3.mov

</details><br />

## Testing Instructions
Write a list of things to test your changes


## Additional Changes
N/A - otherwise, write list of refactors/fixes


## Quick Checklist
Code
- [x] remove logging
- [x] remove comments
- [x] app - memoization and useEffect dependency arrays
- [x] graph_api - check `migrations/_current.json`
  - [x] increment revision number
  - [x] remove personal ref (eg: `"path": "/Users/tim/Documents/GitHub/rewst-app/packages/graph_api/migrations/_current.json",`)
- [x] graph_api - check mutation resolver has `verifyUserManagesOrg` or other security checks
- [x] run linting (remove this checkbox when we add pre commit hooks)

Testing
- [x] unit tests
- [x] integration tests
- [x] Playwright tests

Dependencies
- [x] app
- [x] graph_api
- [x] graph_api database migrations
- [x] engine
- [x] engine YAML packs, actions, and sensors
---
### PS: Don't forget to add labels