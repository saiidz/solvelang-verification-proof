# solvelang-verification-proof

This repository is a **test fixture** for the SolveLang Verification check.

It exists for one purpose: to prove, end to end, that the "SolveLang
Verification" GitHub App grades pull requests honestly — a defective PR
must be caught, and a clean PR must come back clean. It is not a product
and contains no real code.

## Layout

- `src/add.js` — one tiny function.
- `test/add.test.js` — tests for it, run with Node's built-in test runner
  (zero dependencies).
- `.github/workflows/test.yml` — runs the test suite on every pull
  request.
