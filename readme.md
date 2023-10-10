#demo

const c =require('lodash')
const items=[1,[2,[3,[4]]]]
const newitems=c.flattenDeep(items);
console.log(newitems);
