# module_VLE_map

*  [MODULE_VLE_MAP_ID](#module_vle_map_id) **
*  [MOD_INSTANCE_ID](module_instance.md#mod_instance_id) [1] *
*  [VLE_MOD_ID](#vle_mod_id) [1]

\** indicates that the property is the primary key for this entity; if not provided by data supplier, will be LRW generated.  

\* indicates that the property has a uniqueness constraint for this entity. The default is that MOD_INSTANCE_ID and VLE_MOD_ID form a uniqueness constraint. For institutions where MOD_INSTANCE_ID values in module_VLE_map must be unique, see the [MODULE_VLE_MAP_MODE](institution.md#module_vle_map_mode) property in the institution entity.

## Description of module_VLE_map entity
A module_VLE_map links a module in a student record system with module materials in a VLE.

## MODULE_VLE_MAP_ID
### Description
Primary key. Where not supplied by data provider, the primary key will be generated by the LRW loading mechanism.

### Purpose
Enables easy reference to the map between module and VLE.

### Derivation
Jisc

### Format
String (255)

### Notes
Where not supplied by data provider, the primary key will be generated by the LRW loading mechanism.

## VLE_MOD_ID
### Description
An identifier for a course area in the VLE. 

### Purpose
Display in student app and staff dashboard

### Derivation
Jisc

### Valid values
Any

### References

### Format
String (255)

### Notes
The VLE course area may or may not correspond to one module.
