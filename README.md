## How I review Pull Requests

Comments on Pull Requests aren't all equal - some are more important than other. However, visually they are all the same. In order to tackle this I use the following "traffic light" approach to comments:

- 🟩 COULD resolve in this PR - might be more of a subjective style or suggestion. Feel free to implement, discuss or ignore.
- 🔶 SHOULD resolve in this PR - this is something where there is a compelling reason to make improvements. Ideally should be commented on but merging can proceed without implementation.
- 🔴 MUST resolve in this PR - this is something breaking, wrong, or likely to cause substantial misunderstanding. PR won't be accepted until either an agreement is reached or the code is changed
