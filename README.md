

# CI-CD-for-Databases
**CI/CD DevOps Integration for Databases - Snowflake**







**Roolback**
**Reason 1: Database environments aren’t in sync**
We call this configuration drift. Over time, each database environment, from Dev to QA, no longer matches Production. Ultimately, this means when database changes are tested in QA, it’s wasted effort because it’s not a true test. What’s the point of testing if what you’re spending time and effort on isn’t the same anyway?

**Reason 2: Too many changes happen all at once**
Many rollback scripts are executed in huge numbers, late at night. There’s no way that DBAs would be able to review and understand the impact of each change because there’s just too much going on. The sheer volume of changes leads to misses. No one knows there’s a problem until customers start complaining about performance issues. At that point, it’s extremely difficult to find the problem. DBAs often have no choice but to roll back all of the changes, which means losing valuable data collected after the change was made to begin with.A simple DB rollback is now out of the question. The DBAs will need to break down the changes and figure out a way to protect the data gathered since the change. This is a LOT of work (which means a lot of time and money lost).

