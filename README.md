# ES6-
A repository to practise ES6+ related questions.

## Try converting these codes to ES6 syntax-
### que 1
```
var multiply = function(x, y) {
  return x * y;
};
```
### ==>
```
var multiply = (x,y) => x * y;
```
### que2
```
var customer = {
  name: "Bhaalo"
};
var card = {
  amount: 20,
  product: "Aaalo",
  unitprice: 50
};
var message = "Hello " + customer.name + " wants to buy " + card.amount + " " + card.product + " for price of " + card.unitprice + " per piece"
```
### ==>
```
const {name} = customer
const {amount,product,unitprice} = card
var message = `Hello ${name} wants to buy ${amount} for price of ${unitprice} per peice`

```

### que 3
```
var a = 5;
var b = 10;
console.log("Fifteen is ".concat(a + b, " and n0t ").concat(2 * a + b, "."));
```
### ==>

```
var a = 5;
var b = 10;
console.log(`Fifteen is ${a+b} and not ${2 * a + b}`);
```
