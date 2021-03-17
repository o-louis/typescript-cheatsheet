# TypeScript Cheatsheet

## Primitives
```js
string, number, boolean
```
## Array
```js
Array, Array<string>, Array<number>, Array<any>
string[], number[], any[]
```
## Object
```js
obj: { firstname: string, lastname: string }
```
## Function
```ts
const sayHi = (prefix: string): string => `${prefix} Hello`
```
## Interface
```ts
interface Person {
  gender: string;
}

interface User extends Person {
  id: number;
  firstname: string;
  age?: number;
}
```
## Type
```ts
type Point = {
  x: number;
  y: number;
};
```
## Union Type
```ts
type Door = "open" | "closed"
function print(text: string | string[]) {}
```
