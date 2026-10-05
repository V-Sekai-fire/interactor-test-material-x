# interactor-test-material-x

An engine test project with an editor import plugin that turns MaterialX documents into materials.

## What it is for

The plugin registers an importer for `.mtlx` files and hands each one to the engine's MaterialX loader class, so it needs an engine build that provides that class. The project carries a sample model with its MaterialX material and the MaterialX standard libraries.

## Build and run

Open the project in the editor of such a build; importing a `.mtlx` file produces a material.

## Licence

MIT; see LICENSE. The vendored MaterialX libraries keep their own licence.
