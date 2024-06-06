# 3. Restrict data visibility with modules

## Overview

Encapsulate globally accessible data, such as common blocks, within modules.
This approach allows for controlled access interfaces, improving code
readability and minimizing side effects from global data storage.

## Checks

- [PWR073](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR073):
  Transform common block into a module for better data encapsulation.

- [PWR069](https://github.com/codee-com/open-catalog/blob/main/Checks/PWR069):
  Use the keyword only to explicitly state what to import from a module.

- _Planned: Minimize mutable module variables by passing data as procedure
  arguments._

- _Planned: Privatize mutable module variables and add procedures for more
  controlled access._
