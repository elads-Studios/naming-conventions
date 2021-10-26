# Enumeration

Single objects sometimes are composed from multiple resources like for example a sprite animation, or variations of the same asset, that can't be described with words, but with an index.

## Definition

Every index starts at 0, where the next index increments by one from the previous one.

In case of naming indices have to be suffixed with an underscore and the index in question in decimal.

The number of digits must be constant for each object.

## Examples

### ✔️ Good

- ✔️ MyFile_0, MyFile_1, MyFile_2
- ✔️ SomeObject_00, SomeObject_01, SomeObject_02, ...

### ❌ Bad

- ❌ MyFile_1, MyFile_2, MyFile_3
- ❌ 0_MyFile, 1_MyFile, 2_MyFile
- ❌ MyFile0
- ❌ SomeObject_00, SomeObject_01, SomeObject_2, ...

---

Next: [Exceptions with file names](Exceptions%20with%20file%20names)