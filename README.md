# paystack2

### Introduction
The new Nodejs API wrapper for Paystack

You might be thinking why a new Nodejs library if we already have one, well as it is the current library is deprecated and is no longer maintained also Paystack's api now has version 2.

So this will serve as a replacement and I will make sure this is actively maintained

**Note**: This library uses version 2 api docs

> This libray is currently under development and has not been publish to npm yet follow the code in transaction.ts in the resource folder to structure write other resource

### Documentation
For the paystack api reference, see [v1](https://developers.paystack.co/reference) and [v2](https://developers.paystack.co/v2.0/reference)

### Installation (npm package coming soon)
`$ git clone https://github.com/sheghun/paystack2.git`
`$ npm install || yarn add`

### Usage

#### Basic
import the entry file and create a instace of Paystack

```ts
// import entry file
import Paystack from "../index"

const { KEY } = process.env;
```

const paystack = new Paystack();

