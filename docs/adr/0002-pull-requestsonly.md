# 0002 - Changes reach main through pull requests only

## Context
Before pull requests, changes could be pushed directly to main.
There was no required review before a change became part of the count.
This made it harder to catch mistakes and understand why a change was made.

## Decision
Every change must be submitted through a pull request.
Another person reviews the changes before they are merged into main.

## Consequences
- Every change gets a review, making mistakes easier to catch.
- Pull requests provide a place to explain why a change is needed.
- Changes take longer because someone must review them before merging.
- Work cannot enter main immediately, even when the change is small.
