# replace-bash

# Introduction

Bash script to replace words omitting desired directories.

## Configuration

Use the `replace` function in the `code` file, you can copy and paste it in your `~/.bashrc` file.

The directories to omit are defined in the `exclude_dirs` variable, see the `code` file.

# Run

Replace:

```bash
replace old new
```

Replace matching whole word:

```bash
replace -w old new
```

## Test

To test the script works on your computer:

```bash
make test
```
