# Random Name Generator

Zero-dependencies Javascript version of Docker's random container name generator.

Based on: https://github.com/moby/moby/blob/master/pkg/namesgenerator/names-generator.go

## Install

`npm i @afuggini/namegenerator`

## Usage

```
const nameGenerator = require('@afuggini/namegenerator')

const someString = nameGenerator()
console.log(someString) // "awesome_newton"

const anotherString = nameGenerator('-')
console.log(anotherString) // "cocky-davinci"
```
