# Herbivores and Сarnivores

### Description

Nature is well suited to reflect the principles of Object Oriented Programming.
All instances of the `Animal` class must have properties `health` and a `name`.
Health is `100` by default.

Created a `Herbivore` class.
Herbivore has a method of `hide`, which sets the `hidden` property of the beast to the value of `true`, and helps to hide from carnivores.

Created a `Сarnivore` class.
Carnivore has a `bite` method, which takes a herbivore object and decreases the object's health by `50`. The method does not work if it is another сarnivore, or the herbivore is currently hiding.

`Herbivore` and `Сarnivore` extend an `Animal` class.

All alive animals are in the static `Animal.alive` array.
If the health of the animal becomes less than or equal to `0`, the beast dies and it is removed from the static array `Animals.alive`.
  
### Stack

- JS

### Tools

- ESlint
- Prettier
- Jest
