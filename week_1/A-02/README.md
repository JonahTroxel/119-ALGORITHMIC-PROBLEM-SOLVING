# AL02: Library Catalog Lookup and Big-O Recognition

Name: [JONAH TROXEL]
Partners: [ELIJAH FERRER]
Shared repository: [(https://github.com/JonahTroxel/Al02-Jonah-and-Elijah-.git)]
My contribution: In the end, I did all of the actual coding but we brainstormed throughout for the code and the questions we needed to answer

## Run

Keep main.py, test_assignment.py, catalog_data.py, growth_examples.py,
and any other imported modules together.

```powershell
py -3.14 main.py
py -3.14 test_assignment.py
```

## Work Notes and Reflections

Append brief observations, challenges, changes, and learnings.
Include a Big-O label and one short reason for each of the four supplied
growth examples, a scan-case observation, and your two workload choices.
Short bullets are sufficient; no separate worksheet, timing table, or essay.

- [Example name: growth label and reason]
- [Observation, choice, challenge, or learning]

first_id:O(1) because it while at most read one entry from records
all_ids:O(n) because it will read every entry in records exactly once
ordered_pairs:O(n^2) because it will read every entry n amount of times because of the two for loops
halving_sizes:O(log n) because it will create a list of a length that closely lines up with log base 2 of size 

a request for a B1 is faster than a request for B4 or an absent ID because the former means that the code can stop at the first entry(O(1)) while the latter has to go through all entries(O(n)). Because of that, the best case scenario is the input "B1"; while the worst case scenario is a three way tie with the inputs "B4", "B5", "".

Thursday's stuff
1. I would recommend that they do not use an index and instead to a simple search of the record
2. I would definitely recommend that they use an index as that would surely be faster
3. building the index requires scanning every entry, copying it, and adding a key that makes it easier to find the right entry later on. this requires more storage as we are copying the entire record and even adding a little something to the beginning of each entry. reusing it means that for a request it simply finds the key that we added ; this differs from reconstructing the index because this searches the entirety of each entry copies it and adds a key to each and then uses the provided key to find on.


## Assistance
I used AI to explain why halving_sizes is O(log n)
[Support used, or none. For AI, identify the tool/task and what you checked,
changed, or rejected. Identify supplied files as supplied.]

## Instructor Comments

[Reserved for instructor feedback.]