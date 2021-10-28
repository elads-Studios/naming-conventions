# Coding conventions

## Code modules

Each code module contains only a class, an abstract class, a structure, an interface, an enumerator or a delegate.

Every code module must be enclosed inside their appropriate namespace to avoid naming collisions with other code modules.

It is prohibited to have code modules in other code modules, as that would make naming more difficult and decrease the maintainibility of code.

Additionally every namespace, class, abstract class, structure, interface, enumerator, delegate, field, property and function need to be documented using XML documentation, so any code documentation generator can produce well documented code.

## Interfacing

Every class, abstract class, structure need to be interfaced! Our goal is to design code that has a nice to work with API, by just exposing important bits.

## Classes, structures, properties and functions

- [PascalCase](PascalCase)

### Examples

### ✔️ Good

- ✔️ PlayerControllerScript
- ✔️ LevelData

### ❌ Bad

- ❌ player_controller_script
- ❌ levelData

## Abstract classes

- Same as [classes, structures, properties and functions](#Classes,%20structures,%20properties%20and%20functions)
- Prefixed with a capital `A`

### Examples

### ✔️ Good

- ✔️ AEntityControllerScript
- ✔️ ASaveGameData

### ❌ Bad

- ❌ EntityControllerScript
- ❌ BaseSaveGameData

## Interfaces

- Same as [classes, structures, properties and functions](#Classes,%20structures,%20properties%20and%20functions)
- Prefixed with a capital `I`

### Examples

### ✔️ Good

- ✔️ IEntityController
- ✔️ ISaveGameData

### ❌ Bad

- ❌ EntityController
- ❌ SaveGameDataInterface

## Function parameters

- [camelCase](camelCase)

### Examples

### ✔️ Good

- ✔️ playerController
- ✔️ gridSize

### ❌ Bad

- ❌ player_controller
- ❌ szGrid

## Fields

- Same as [function parameters](#Function%20parameters)
- Field must be always private

## Local variables

- [snake_case](snake_case.md)

---

Next: [Coding patterns](Coding%20patterns.md)