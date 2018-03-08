# ET's opinionated backbone generator

## Usage

Install: `npm install -g generator-etbackbone`

Make a new directory and `cd` into it:
```
mkdir my-new-project && cd $_
```

Run `yo etbackbone`, optionally passing an app name:
```
yo etbackbone [app-name]
```

## Generators

Available generators:

- etbackbone:model
- etbackbone:view
- etbackbone:collection
- etbackbone:router
- etbackbone:all

## Typical workflow

```
yo etbackbone # generates your application base and build workflow
yo etbackbone:model blog
yo etbackbone:collection blog
yo etbackbone:router blog
yo etbackbone:view blog
grunt serve
```
