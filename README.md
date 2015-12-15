# math-permutation(数学排列)

## Install
	npm i math-permutation --save

## Usage
	var permutation = require('math-permutation')
	var arr = [1, 2, 3]

	//Get all conditions that conbine two element of the the arr(different order different condition)
	combination.cmn(arr, 2)

	//Get all conditions that conbine two element of the the arr(different order different condition and element can repeat)
	combination.cmnWithRepetition(arr, 2)

--- 

### Note
Only support for array of String or Number

---

### See [test](https://github.com/likegun/math-permutation/blob/master/test/index.js) for more details
