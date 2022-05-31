# BaseGraph extension example

A minimal example to show how to extend [BaseGraph]. Add this extension to BaseGraph by running the following command in the BaseGraph repository
```sh
./bg extension create extension_ex https://github.com/SILIZ4/BaseGraphExtensionExample.git
```
To make the new extension available to other projects, recompile and reinstall BaseGraph C++ library
```sh
./bg install cpp
```

[BaseGraph]: https://github.com/antoineallard/base_graph
