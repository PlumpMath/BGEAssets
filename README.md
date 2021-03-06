# BGEAssets
Collection of assets for Blender Game Engine. ![License information](./LICENSE.txt?raw=true)

## Examples
![Carnival Collection](./preview.png?raw=true)

# About the Code Style Guide
 * General: https://www.python.org/dev/peps/pep-0008/
 * Docstrings: https://www.python.org/dev/peps/pep-0257/

# About the Art Style Guide
The style guide is broken into two parts.
 1. General Bender Style Guide contained within the root README, covering technical elements as units of measurement, object, vector and material namign conventions within blender. General Blender Style Guide rules apply to all child files and folders.
 2. Collection Style Guide, contained within each collections base folder README covering asthetic rules such as model asthetics, use of colour, lighting, etc. Collection Style Guide rules only apply to that specific collections files and folders.

# General Bender Art Style Guide
## Units of measurement
Metric units should be used at a scale of 1:1 so that the blender object measurements are within range of a real life representation of the object.

## Name Conventions

### Objects
Blender objects should be named with the most accurate representation of what they are.
They should be postfixed with their number count to the 3rd decimal place, starting at zero.
Blender objects should be postfxied with their number count to the 3rd decimal place, starting at zero.

Template: `<object name>.<count>`
For example, a single "shoe" would be "shoe.000", two shoe objects would be "shoe.000" and "shoe.001"

### Vector Groups
Blender vector groups should be named with the most accurate representation of what the vector group contains.
Vector groups should be prefix with the object name, hyphenated then the vector group name, followed by a postfix of the group count.
Blender vertex groups should be postfxied with their number count to the 3rd decimal place, starting at zero.

Template: `<object name>-<vector-group>.<count>`
For example, a single "shoe heel" would be "shoe-heel.000", two shoe objects would be "shoe-heel.000" and "shoe-heel.001"

### Materials
Blender materials should be named with the most accurate representation of what they are.
They should start with the material name, hypenated with the closest colour name, with a decimal followed by a postfix of the count.
Blender materials should be postfxied with their number count to the 3rd decimal place, starting at zero.

Template: `<material>-<colour>.<count>`
Example: A single leather material would be "leather-brown.000", where as multiple leather materials could be "leather-brown.000", "leather-brown.001", "leather-red.000"

### Textures
Blender elements should be named with the most accurate, real world example, of what they are.
Texture groups should be prefixed by the blender material they're being used for, followed by the map type (bump, normal, displacement, light, etc), postfixed by the count.
Blender textures should be postfxied with their number count to the 3rd decimal place, starting at zero.

Template: `<material>-<map-type>.<count>`
Example: A single leather texture would be "leather-bump.000", where as multiple leather textures could be "leather-bump.000", "leather-bump.001", "leather-light.000", "leather-normal.000"


