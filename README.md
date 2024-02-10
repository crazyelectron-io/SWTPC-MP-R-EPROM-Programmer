# SWTPC MP-R EPROM Programmer

SWTPC MP-R EPROM Programmer schematics and documentation.

## Custom parts library

This repository uses a custom parts repository as submodule.
Use the command `git submodule add https://github.com/crazyelectron-io/KiCAD_custom_parts.git hardware/library/custom_parts` once in the root of the project (after initial creation).
When later committing the MP-R repository, the submodule dependency is also registered and when cloning it again, run the following commands to get the submodule(s) back:

```bash
git submodule init
git submodule update
```

To use the updated libraries after a custom part is added or updated, just run `git submodule update` to retrieve the changed libraries.
