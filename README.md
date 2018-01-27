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
