# ad

**A shorthand CLI for directory and file creation**

## Installation

```shell

npm install -g add-new

```

## Usage

```shell
ad [options] <path> [morePaths...]

Options:
  -V, --version  output the version number
  -t, --tree     display result tree
  -d, --debug    debug messages on
  -h, --help     output usage information
```
### Examples

```shell
$ ad src/components/todo-{list,item}.{ts,scss} -t
```

result:

```shell
src
|____components
| |____todo-item.ts
| |____todo-item.scss
| |____todo-list.scss
| |____todo-list.ts


```
