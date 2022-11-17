# container-crystfel

Install as a module share module using `shpc`.

```
# Install
cd /path/to/registry
git clone git@github.com:rosalindfranklininstitute/container-crystfel.git
shpc install crystfel

# Update
cd /path/to/registry/crystfel
git pull
shpc install crystfel

# Usage
module load crystfel

# Open crystfel GUI by running
crystfel

# Run commands against the container
crystfel-run which crystfel
# gives the path within the container to the install location
/usr/local/crystfel/bin/crystfel

# Print the module usage help
module help crystfel
```

This module aliases `crystfel` to `/usr/local/crystfel/bin/crystfel` within the container. 