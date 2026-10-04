# relock-fixture

A temporary probe for `dotnet-software-factory`. `App` references `Lib`, and `Lib` references one package. Dependabot opens a pull request here, and the two `relock-fixture-*` workflows run on it.

The probe moved `main` one time, to test a Dependabot rebase.

The probe moved `main` a second time, for the control.
