# 5. Improve data type consistency and management

## Overview

Ensure the consistency of data types by avoiding implicit typing and
standardizing the code on a fixed set of real kinds, improving readability and
portability across different development environments. Use derived data types
to represent complex multi-field structures. Leverage pointers and allocatable
arrays for safer memory handling.

## Checks

- [PWR007](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR007):
  Always use implicit none to disable implicit declarations.

- [PWR071](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR071):
  Prefer real(kind=kind_value) for declaring consistent floating types.

- _Planned: Prefer derived types over constructs such as structure or record to
  represent complex multi-field entities_.

- _Planned: Replace equivalence statements by pointers or the transfer
  intrinsic as needed._

- _Planned: Consider replacing fixed-size arrays with allocatables._
