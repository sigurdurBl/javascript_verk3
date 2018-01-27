# javascript_verk3
1
 template literals eru strengalistar sem leyfa innbyggðum tjáningum.  
 getur notað fjölstrengja strengi og strengaráritun með þeim.
2
For =býr til lykkju sem samanstendur af þremur valkvæðum tjáningum, meðfylgjandi innan sviga og aðskilin með hálfkúlum,
ForEach = aðferðin framkvæmir tiltekna aðgerð einu sinni fyrir hvern array element
for in lykkja lýkur aðeins yfir óteljandi eiginleika. Hlutir sem eru búnar til af innbyggðum smiðjendum eins og Array and Object
hafa erft ótengda eiginleika frá Object.prototype og String.prototype,

3
  a
  Use the MDN Documentation to determine which of these methods would be best for reversing elements in this array:
  var reverseMe = ["h", "e", "l", "l", "o"];
  svar reverse()

  b
  What would be the best array method to sort the elements in this array:
  var sortMe = [2, 1, 10, 7, 6];
  svar sort()
  
  c
  Consider the following array, removeFirstElement:
  var removeFirstElement = ["a", "b", "c"];
  Let's say that you want to modify (i.e., mutate) removeFirstElement by removing the first element within it. Which method(s) could you use?
  svar shift()og splice()
  
  d
  What method would be best for changing this array into a string
  var turnMeIntoAString = ["U", "d", "a", "c", "i", "t", "y"];
  svar join()
4
test.forEach(function addsHundred(value, index) {
    if (value % 3) {
    	value += 100;
    	test.splice(index, 1, value);
    }
});
console.log(test);
5
var totals= bills.map(function(number,index,array) {
                number+= number*0.15;
               return Number((number.toFixed(2)));
            });

console.log(totals);
6
for(var r=0;r < numbers.length; r ++){
    for (var c=0; c< numbers[r].length;c++){
        if (numbers[r][c] % 2 === 0) {
            numbers[r][c]="even";
            console.log(numbers[r][c]);
        }
        else {
            numbers[r][c]="odd";
            console.log(numbers[r][c]);
        }
        }
    }
console.log(numbers);
7
breakfast = {
    name:"The Lumberjack",
    price:9.95,
    ingredients: ["eggs", "sausage", "toast", "hashbrowns", "pancakes"]
};
console.log(breakfast.name, breakfast.price)

console.log(breakfast.ingredients)
8
var savingsAccount = {
    balance: 1000,
    interestRatePercent: 1,
    deposit: function addMoney(amount) {
        if (amount > 0) {
            savingsAccount.balance += amount;
        }
    },
    withdraw: function removeMoney(amount) {
        var verifyBalance = savingsAccount.balance - amount;
        if (amount > 0 && verifyBalance >= 0) {
            savingsAccount.balance -= amount;
        }
    },
    printAccountSummary: function() {
        var message = "Welcome!\nYour balance is currently $"+savingsAccount.balance+" and your interest rate is "+savingsAccount.interestRatePercent+"%.";
        return message;
    }
};

console.log(savingsAccount.printAccountSummary());
9
donuts.forEach(function(donut) {
  console.log(donut.type + " donuts cost $" + donut.cost + " each"); 
  
