---
date: 2020-09-22T16:40
---

# Sum Type

A data type consisting of two or more distinct branches with different
representations. For example, the following [[Haskell]] data type might be used
to identify a user in an information system:

```haskell
data IdOrEmail = Id UserId | Email EmailAddress
```
