# 7. Enhance source code semantics

## Overview

Leverage elements from recent Fortran standards to further improve the clarity
and intent of code statements beyond previous recommendations.

## Checks

- [PWR003](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR003):
  Explicitly declare pure functions.

- [PWR072](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR072):
  Split the variable initialization from the declaration to prevent the
  implicit 'save' behavior.

- _Planned: Prefer variable initializations at declaration instead of data or
  block data statements._

- _Planned: Add an explicit parameter attribute to constant variables._

- _Planned: Explicitly declare elemental functions._
