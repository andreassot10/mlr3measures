# mlr3measures 0.2.0-9000

# mlr3measures 0.2.0

* Added new measures: `mauc_au1p`, `mauc_au1u`, `mauc_aunp`, and `mauc_aunu`.
* Fixed noLD check warnings.

# mlr3measures 0.1.3

* Added a `packageStartupMessage()` advising against attaching this package.
* Added new measure `bbrier` (binary Brier Score).
* Added new measure `mbrier` (multi-class Brier Score).
* Improved numerical stability for measure `mcc`.

# mlr3measures 0.1.2

* Fixed integer overflows in `auc`, `dor` and `mcc`.

# mlr3measures 0.1.1

* Added new measure `bacc` (Balanced Accuracy).
* Fixed some tests which stochastically failed.
* The name of the measure is now also stored in the meta data.

# mlr3measures 0.1.0

Initial release.
