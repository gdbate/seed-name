# seed-name

A simple name randomizer for seeding databases (or whatever you want).

##Features:

* Very simple, no dependancies.
* First (female, male, both) names or last name generation.

##Initialize

```javascript

var seedNames = require('seed-names');

```
## Seed a female name

```javascript

seedNames.first( 'female' );

```

## Seed a male name

```javascript

seedNames.first( 'male' );

```

## Seed a first name (both genders)

```javascript

seedNames.first();

```

## Seed a last name

```javascript

seedNames.last();

```

*Note:* Generated from the 1000 top names in the US.

## To Do

* Actually test it .. once..
