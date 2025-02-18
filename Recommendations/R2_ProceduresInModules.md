# 2. Declare procedures in modules

## Overview

Declare related procedures within an importable module to enhance code
modularity, reusability, and readability. This practice also helps avoid
runtime errors related to implicit interfaces. Separate the definition of
procedures into modules and their implementation into submodules, leveraging
incremental compilation to reduce build times.

## Checks

- [PWR068](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR068):
  Encapsulate procedures within modules to avoid the risks of calling implicit
  interfaces.

- _Planned: Consider moving the module's procedure implementations into a
  separate submodule._
