# factory-scratch

Scratch repo for the `dotnet-software-factory` integration tests. Each test creates the issue, pull request or review thread it reads.

The one exception is a check run. A token cannot create one, so `.github/workflows/fixture.yml` ran one time by hand. Its check run `fixture` on that commit is the fixed answer the check-run test reads.
