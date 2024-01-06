```bash
pdm add $package_name
```

example:

```bash
pdm add requests
```

### install dev group dependencies

```bash
pdm add -dG $group_name $package_name
```

example:

```bash
pdm add -dG test pytest
pdm add -dG lint ruff
```