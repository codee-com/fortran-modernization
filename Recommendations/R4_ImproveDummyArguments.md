# 4. Improve dummy arguments semantics

## Overview

Enhance the definitions of dummy arguments to make the behavior of procedures
more predictable and transparent, helping avoid common issues related to
incorrect assumptions about data type, flow, or structure.

## Checks

- [PWR008](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR008):
  Declare the intent for each procedure argument.

- [PWR070](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR070):
  Declare array dummy arguments as assumed-shape arrays.

- _Planned: Add a contiguous attribute to applicable assumed-shape arrays._
