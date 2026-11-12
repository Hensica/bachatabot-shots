# visual-changelog (bot-managed)

Screenshots of Hensica's products, written by GitHub Actions bots. Pull-request comments show
them inline, and each sprint cycle's close-out compares its before and after sets.

- `<project>/pr-<N>/<date>-<sha7>/`: one set per pull request, holding the renders it changed
  and, as `before-<file>`, the same renders at the commit its branch started from. Deleted after
  the project's retention setting (14 days unless the project sets another).
- `<project>/cycles/<id>/before/` and `<project>/cycles/<id>/after/`: the product when a sprint
  cycle's plan merged and when the cycle closed. Kept, so cycles can be compared later.
- **No personal data, ever.** Every image is rendered from synthetic data only. No real account
  and no real user data appear.
- **Do not edit.** Each update rewrites the branch as a single commit, so a deleted image also
  leaves the branch history.
