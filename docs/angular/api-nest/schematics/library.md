# library

Create a new nest library

## Usage

```bash
ng generate library ...
```

```bash
ng g lib ... # same
```

By default, Nx will search for `library` in the default collection provisioned in `angular.json`.

You can specify the collection explicitly as follows:

```bash
ng g @nrwl/nest:library ...
```

Show what will be generated without writing to disk:

```bash
ng g library ... --dry-run
```

### Examples

Generate libs/myapp/mylib:

```bash
ng g lib mylib --directory=myapp
```

## Options

### controller

Default: `false`

Type: `boolean`

Include a controller with the library

### directory

Alias(es): d

Type: `string`

A directory where the app is placed

### global

Default: `false`

Type: `boolean`

Add the Global decorator to the generated module.

### linter

Default: `tslint`

Type: `string`

Possible values: `eslint`, `tslint`

The tool to use for running lint checks.

### name

Type: `string`

Library name

### publishable

Alias(es): buildable

Type: `boolean`

Create a buildable library.

### service

Default: `false`

Type: `boolean`

Include a service with the library.

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting files

### skipTsConfig

Default: `false`

Type: `boolean`

Do not update tsconfig.json for development experience.

### tags

Alias(es): t

Type: `string`

Add tags to the library (used for linting)

### target

Default: `es6`

Type: `string`

Possible values: `es5`, `es6`, `esnext`, `es2015`, `es2016`, `es2017`, `es2018`, `es2019`, `es2020`

The es target, Nest suggest using es6 or higher.

### testEnvironment

Default: `node`

Type: `string`

Possible values: `jsdom`, `node`

The test environment for jest, for node applications this should stay as node unless doing DOM testing.

### unitTestRunner

Default: `jest`

Type: `string`

Possible values: `jest`, `none`

Test runner to use for unit tests
