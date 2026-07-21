# UnitsOfMeasurement
An extensive list of units of measurement and their conversion factors<br>
The conversion units follow a star topology as opposed to a loop or web, with one unit, typically the SI unit, as the center. This allows O(n) conversion factors while minimizing rounding errors. In some dimensions, there are more than one center. For example, the length dimension has a 'meters' and a 'feet' center.  This is because a foot can be defined as many different lengths, and I cannot be certain which foot any unit is referring to.

## Table Documentation

### `name`

The common name of the unit of measurement. If there are alternate spellings, they will be separated with a vertical bar character | .

### `symbol`

The common symbol of the unit. Will be blank if there is no common symbol.

### `factor`

The factor of the unit compared to the base unit (except for length, see below). The base unit is the first unit listed in each file. This can have scientific notation (for example 1e40, or 1e-20) or fractions (for example 355/113).

### `ft/m/pt` (Length Only)

Determines if the factor is based on the meter (m), the foot (ft), or the point (pt).

#### Why?
todo: explain

### `approximate/exact`

todo: explain

### `source`

todo: explain

## useful links

https://en.wikipedia.org/wiki/List_of_conversion_factors

https://en.wikipedia.org/wiki/List_of_obsolete_units_of_measurement

https://en.m.wikipedia.org/wiki/List_of_unusual_units_of_measurement

https://en.m.wikipedia.org/wiki/List_of_humorous_units_of_measurement

https://en.m.wikipedia.org/wiki/System_of_units_of_measurement

https://en.wikipedia.org/wiki/Medieval_weights_and_measures

https://commons.wikimedia.org/wiki/File:English_Length_Units_Graph.svg
