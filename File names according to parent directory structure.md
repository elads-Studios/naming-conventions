# File names according to parent directory structure

Every file name should be named after how their parent directories are structured. Even though this may sound reduntant, but actually helps finding assets quickly according to for what they have been grouped into.

If a directory may contain multiple types of assets, then they have to be named plural

The most significant information have to be on the left side, since we read from left to right in English. Then to the right we the sub-groups/groups and type of the file.

To build such name, you have to build it from right to left. Starting with the type of the file going to what they have been categorized into then finally the subject of that file.

## Examples

### ✔️ Good

- ✔️ ./Assets/Meshes/Entities/Characters/Player/HeadPlayerCharacterEntityMesh.dae
- ✔️ ./Assets/Scripts/Controllers/WalkingCharacterControllerScript.cs

### ❌ Bad

- ❌ ./Assets/Meshes/Entities/Characters/Player/HeadPlayerCharacterEntityMesh.dae
- ❌ ./Assets/Meshes/Entities/Characters/Player/HeadPlayerMesh
- ❌ ./Assets/Meshes/Entities/Characters/Player/PlayerHeadMeshCharacterEntity

---

Next: [Self documenting names](./Self%20documenting%20names.md)