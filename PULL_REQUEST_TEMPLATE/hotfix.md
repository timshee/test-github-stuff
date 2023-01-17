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