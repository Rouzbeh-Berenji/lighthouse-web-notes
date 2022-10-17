### info :
working on small code to work with comparision oparators and using nested if to define a function 
```javascript
const whatToDoForLunch = function(hungry,availableTime) {
  console.log("I don't know what to do!");
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);

  if (hungry) {
    if (availableTime < 20) {
      return "pick up a snack or grab something you have ready at home.";
    } else if (availableTime >= 20 && availableTime <= 30) {
      return "you deserve a break and should take time to cook a tasty meal.";
    } else if (availableTime > 30) {
      return "this is an intense program after all and you should probably reconsider.";
    }
  } else {
    return "Continue your work on Bootcamp";
  }
};
```