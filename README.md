# `@jsfeb26/streak-counter` - a basic streak counter

This is a basic streak counter - inpsired by Duolingo - written in Typescript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @jsfeb26/streak-counter
npm i @jsfeb26/streak-counter
```

## Usage

```js
import { streakCounter } from "@jsfeb26/streak-counter";

const today = new Date();
const streak = streakCounter(localStorage, today);
// streak returns an object:
// {
//   currentCount: 1,
//   lastLoginDate: "11/11/2021",
//   startDate: "11/11/2021",
// }
```
