# Dart Linux Package Repository – Source Codes

This repository hosts the **Dart Linux package sources**.

## Branch Structure

* Branches prefixed with `sources-` (e.g., `sources-dattrin`) are **independent branches** containing the **source code** for the corresponding packages stored in the normal branches.
* Normal branches (e.g., `dattrin`) contain the **compiled packages** or package metadata.

## Example

| Branch            | Contents                               |
| ----------------- | -------------------------------------- |
| `dattrin`         | Compiled packages and metadata         |
| `sources-dattrin` | Source code for the `dattrin` packages |

> Note: Changes in `sources-` branches do **not** affect the normal branches automatically. They are maintained separately.
