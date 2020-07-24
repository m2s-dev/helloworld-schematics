# Getting Started With Schematics

This repository is a basic Schematic `Hello world` implementation that serves as a starting point to create and publish Schematics to NPM.

## Install

To test locally, install `@angular-devkit/schematics-cli` globally 

```bash
npm i -g @angular-devkit/schematics-cli
```

```bash
npm install
```

## Development

### Build
```bash
npm run build
```

### Testing schemmatic
```bash
schematics .:helloworld --name=Martin --debug=false --force
```
`--force` override/delete exists file

### Testing

Use the `schematics` command line tool. That tool acts the same as the `generate` command of the Angular CLI, but also has a debug mode.

Check the documentation with
```bash
schematics --help
```

### Unit Testing

`npm run test` will run the unit tests, using Jasmine as a runner and test framework.

### Publishing

To publish, simply do:

```bash
npm run build
npm publish
```

That's it!
 