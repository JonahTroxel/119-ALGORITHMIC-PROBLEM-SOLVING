# AL03: Ticket Registry, Queue, and Undo

Name: [Jonah Troxel]
Partners: [Dylan U]
Shared repository: [https://github.com/ube8970-SWTC/Algorithms_paired_Dylan_Jonah.git]
My contribution: [I did the coding on monday while brainstorming with my partner in which we finished what was assigned on monday and started on tuesday. I then checked over the work done by my partner in which finished tuesday and thursday's work.]

## Run

Keep main.py, test_assignment.py, ticket_data.py, ticket_display.py,
console_style.py, and any other imported modules together.

```powershell
py -3.14 main.py
py -3.14 testing_1.py
```

## Operation Comparison

One short reason per row is enough. Compare list and dictionary behavior;
do not implement every operation twice or maintain two live stores.

| Operation | Representation fit / reason |
| --- | --- |
| Find one ticket by ID | [dictionary because that would be O(1) always while a list could be up to O(n)] |
| Update one ticket's priority | [dictionary because if the ticket is not in the dictionary then it only takes a O(1) to check that. the n to change it also only take another O(1) if you have the ID and a O(n) if you don't] |
| Select tickets in a category | [a set would be a list of the categories and which ID's are in each category. this makes it so that to see each ticket in a category you don't have to search the whole database] |

## Work Notes and Reflections

while we were doing the assignment we stumbled upon a way to write in a .py file and I might use that in a personal project
Append brief observations, debugging challenges, changes, and learnings.

- Processing and undo: [when you undo ticket T302 it goes back to pending/open and the rest stay the same]
- Contract or snapshot learning: [we have to ensure that every list/dictionary/other is properly updated for every action]

These can be short bullets, not an essay or separate evidence document.

## Assistance

[we used AI to discover the way to write to a .py file and my partner used it to add the repair que function]

## Instructor Comments

[Reserved for instructor feedback.]