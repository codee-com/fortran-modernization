# 1. Strict compliance with modern Fortran standards

## Overview

Remove legacy features deleted from recent Fortran standards, as they might not
be supported by recent compilers, and avoid compiler-specific extensions,
ensuring that the code remains compatible across various development
environments.

## Checks

- [PWR075](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR075):
  Avoid using GNU Fortran extensions.

- _Planned: Tune compiler flags to mark features removed from recent Fortran
  standards._

- _Planned: Tune compiler flags to mark compiler-specific constructs._
