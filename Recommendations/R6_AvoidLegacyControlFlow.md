# 6. Avoid legacy control-flow constructs

## Overview

Replace outdated and error-prone control-flow constructs with more robust and
maintainable language features from recent standards, improving code
maintainability and reducing the likelihood of bugs.

## Checks

- [PWR063](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR063):
  Avoid using legacy Fortran constructs.

- _Planned: Use case or if-then-else constructs instead of go to statements for
  conditional flow._

- _Planned: Use do, cycle, and exit constructs instead of go to statements for
  loops._

- _Planned: Replace arithmetic if statements with block if constructs._

- _Planned: Convert numbered do loops to modern do loops._

- _Planned: End all loops with an end do statement._

- _Planned: Use only integer control variables in do loops._

- _Planned: Replace forall statements with do-concurrent constructs._

- _Planned: Avoid alternate return statements._

- _Planned: Replace compiler-dependant short-circuit logic with nested
  conditionals._
