# # Lab 04 - Automated Software Testing

## Group Name
NUMB

## Who Did What

| Member | ID | Task |
|---|---|---|
| Phyo Maung Maung | 6805140043 | Task A - test_deposit.py; Task E - conftest.py |
| Lynn Myat | 6805140036 | Task B - test_withdraw.py |
| Paing Hein Khant | 6805140039 | Task C - test_teardown.py |
| Than Htike Aung | 6805140050 | Task D - test_shared.py |
## Reflection Questions

| Question | Answer |
|---|---|
| **1. Why was your push rejected, and how did you fix it?** | My push was rejected because the remote repository contained commits that were not in my local repository. I used `git pull` to integrate the remote changes, resolved the merge conflict, committed the merge, and then pushed again. |
| **2. Why could Git not resolve the README conflict automatically?** | Git could not resolve the README conflict automatically because different group members changed the same part of the file. We manually combined the changes so that all members' information was kept. |
| **3. What is the difference between committing and pushing?** | A commit saves changes to the local Git repository, while pushing uploads those commits to GitHub so that other team members can see them. |
| **4. How do fixtures reduce duplicated setup code in tests?** | Fixtures provide reusable setup code that can be used by multiple tests. This avoids writing the same setup code separately in each test. |
