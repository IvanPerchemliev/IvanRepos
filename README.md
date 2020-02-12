var array = new Array(2, 3, 42, 5, 6, 23, 4, 5, 6, 78, 8, 1, 2, 3, 55, 22, 1, 2, );
var newArray = [];
for (var i = 0; i < array.length; i++) {
  if (array[i] > 21) {
    newArray.push(array[i]);
  }
}
console.log(newArray);
