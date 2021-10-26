# Coding patterns

In Unity Engine we use the Controllers pattern.

## Controller

A controller describes a script or behaviour of an instance.

## Trigger

A trigger is a special type of controller that destroys itself once it has served a purpose. Once a trigger has served their purpose, they are no longer needed, so keeping them active in a scene would waste resources running their logic.

Triggers are used for example for reading and applying settings in the beginning of a game.

## Manager

A manager is a special type of controller that is a singleton that manages a group of controllers like for example a game manager would be responsible for holding centralized logic and data for game related data, while other controllers can register events or poll from or push data to that manager.

## Helpful packages

- [https://github.com/BigETI/UnityPatterns](https://github.com/BigETI/UnityPatterns) helps us to write code using the Controllers pattern.
- [https://github.com/BigETI/UnityEngineInterfaces](https://github.com/BigETI/UnityEngineInterfaces) contains a set of interfaces used by [UnityPatterns](https://github.com/BigETI/UnityPatterns)

---

Next: [camelCase](./camelCase.md)