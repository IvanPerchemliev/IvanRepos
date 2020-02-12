var input = new Array(9,3,4.3,24,54,8,19,23,46,87,3.14);
    var output = new Array();
    for (var i = 0; i < input.length; i ++) {
	if (input [i] > 5){
      output.push(input.slice(i, i + length).join(" "));
}
    }
console.log(output);
