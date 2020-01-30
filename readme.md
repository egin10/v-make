# v-make

**v-make** is a command line that will help you to create component with scaffold structure, create module in your store and then automaticatly update the store after the module has created.

## Installation

You can install the v-make by download the file `v-make` in to your project root directory. Make sure you have install `curl` and you can download it with command below :

```
curl https://raw.githubusercontent.com/egin10/v-make/master/v-make --output v-make
```

If the file has downloaded. You can try to check the version with `node v-make -v`.

## CLI Commands

### Component

Create a new component with a simple way, you just need to type comannd below.

```
node v-make component NewComponent
```

or you can try with another simple way.

```
node v-make -c NewComponent
```

The comannd above will create a new component in directory `src/componenets`. if you want to create a new component in new directory, you can try with the command below.

```
node v-make -c newDir/NewComponent
```

The command above will create new component in `src/components/newDir` and the component file's name is `NewComponent.vue`. The `newDir` can more than one directory. If you want to create it deep in, you can type `newDir/newDir/NewComponent`.

### Module

Create a new module with a simple way, you just need to type comannd below.

```
node v-make module NewModule
```

or you can try with another simple way.

```
node v-make -m NewModule
```

The comannd above will create a new module in directory `src/store/modules`. if you want to create a new module in new directory, you can try with the command below.

```
node v-make -m newDir/NewModule
```

The command above will create new module in `src/store/modules/newDir` and the module file's name is `NewModule.js`. The `newDir` can more than one directory. If you want to create it deep in, you can type `newDir/newDir/NewModule`.

### More

You can show the command list with the command below.

```
node v-make help
```

or

```
node v-make -h
```

## Contribution

Please make sure to read the [Contributing Guide](./contributing.md) before making a pull request.

## License

[MIT](./LICENSE)
