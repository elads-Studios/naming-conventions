# Exceptions with file names

Not every name is strictly named according to how their parent directories are structured.

One example would be that directories are written in plural, but each asset does not contain the plural form of heir parent directories.

Another example would be a pre-fabricated (short prefab) object that is suffixed with `Object` instead of `Prefab`, since once a prefab has been intantiated into a scene, it is no more a prefab. Therefore the common name between them would be `Object`, as that would indicate it is linked to an asset, but in runtime it has been resolved to an instance.

## Known exceptions

- Prefab -> `Object` suffix
- Scripts/Runtime -> They follow the [coding conventions](./Coding%20conventions.md)

---

Next: [Coding conventions](./Coding%20conventions.md)