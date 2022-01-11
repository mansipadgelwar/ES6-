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
### que 2
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

### que 4
```
var arr = ["MA", "TA", "PA", "CA"];
var firstName = arr[0],
var surname = arr[1];
console.log(firstName);
console.log(surname);
```
### ==>
```
var arr = ["MA", "TA", "PA", "CA"];
[firstName,surname] = arr;
console.log(firstName);
console.log(surname);
```

### que 5
```
var avengers = {
  operation: "Assemble",
  members: [
    {
      ironMan: "Tony Stark"
    },
    {
      captainAmerica: "Steve Rogers"
    },
    {
      blackWidow: "Natasha Romanoff"
    }
  ]
};
var operation = avengers.operation,
  members = avengers.members;
```
### ==>
```
var avengers = {
  operation: "Assemble",
  members: [
    {
      ironMan: "Tony Stark"
    },
    {
      captainAmerica: "Steve Rogers"
    },
    {
      blackWidow: "Natasha Romanoff"
    }
  ]
};
const {operation,members} = avengers;

```
