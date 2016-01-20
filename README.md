# Kickstart Brunch

Personal brunch io kickstarter with javascript, SASS, eslint and jasmine.

## How to use

You gonna need brunch installed globally in order to use the `new` command.
If you don't like this approach (like me) download this repo and run `npm install`.

#### Using new Command

```
mkdir [PROJECT DIR]
cd [PROJECT DIR]
brunch new --skeleton https://github.com/junior-ales/kickstart-brunch
```

## Running

```
Most important lifecycle scripts included in kickstart-brunch:
  test
    jasmine
  start
    brunch watch --server

available via `npm run-script`:
  lint
    esw app/ --ext .js
  build
    brunch build
  build:prod
    npm run build -- -p
```
