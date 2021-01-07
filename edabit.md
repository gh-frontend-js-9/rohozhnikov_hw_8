### a. Conditions
##### I. Challenge
1. URL: https://edabit.com/challenge/NKknKNfeaJxLDfJuZ
2. Solutions: https://www.dropbox.com/s/xhjj8wrjfl8v4gj/monthName.png?dl=0
##### II. Challenge 
1. URL: https://edabit.com/challenge/RPBqWjEa7iyo9p54F
2. Solutions: https://www.dropbox.com/s/rsit6yap7544utf/numberSyllables.png?dl=0
##### III. Challenge 
1. URL: https://edabit.com/challenge/GJn7xcBiCLdCNXFgy
2. Solutions: https://www.dropbox.com/s/8oheefnaovz5o3m/profit.png?dl=0
##### IV. Challenge 
1. URL: https://edabit.com/challenge/R3AYf3eTdATXTQTdZ
2. Solutions: https://www.dropbox.com/s/zfefnu383sh033q/firstLast.png?dl=0
##### V. Challenge 
1. URL: https://edabit.com/challenge/FydPqxRiosP7EBiQh
2. Solutions: https://www.dropbox.com/s/pxzxddwi0s929xd/countWords.png?dl=0
### b. Arrays
##### I. Challenge 
1. URL: https://edabit.com/challenge/erFxBbqzZPSegMwnc
2. Solutions: https://www.dropbox.com/s/uluuzf9n894frmp/changeEnough.png?dl=0
##### II. Challenge 
1. URL: https://edabit.com/challenge/qMr6wYGr6NaXAPQGF
2. Solutions: https://www.dropbox.com/s/6l5k3lfrm0dgf50/divisible.png?dl=0
### c. Loops
##### I. Challenge 
1. URL: https://edabit.com/challenge/QtcPzxgcZJQdsfdMS
2. Solutions: https://www.dropbox.com/s/dvhnplhtddcxbya/progressDays.png?dl=0
##### II. Challenge 
1. URL: https://edabit.com/challenge/zLYbAPk8NMnwoPhjG
2. Solutions: https://www.dropbox.com/s/62e4e7r8lqmnemc/factorize.png?dl=0
### d. Functional Programming
##### I. Challenge
1. URL: https://edabit.com/challenge/Fev8jkLtDunP9wexv
2.Solutions: https://www.dropbox.com/s/epoawit7jy0g5jw/firstIndex.png?dl=0
##### II. Challenge
1. URL: https://edabit.com/challenge/ENWFBL4jbTgLbSqwS
2. Solutions: https://www.dropbox.com/s/dukdrlnpzecjbje/makePlusFunction.png?dl=0
### e. Scope
##### I. Challenge
1. URL: https://edabit.com/challenge/6ALbTxgu8BZaa6YYN 
2. Solutions: https://www.dropbox.com/s/9v4m79o2nez08r9/numberOfSwaps.png?dl=0
##### II. Challenge
1. URL: 
2. Code:
```javascript
function change(x, times) {
  var x = x.slice()
  for (let i = 0; i < x.length; i++) {
    let j = 1;
    while (j <= times) {
      if (i >= j && i < x.length - j) {
        x[i]--;
      }
      j++;
    }
  }
  return x;
}

let x = [3, 3, 3, 3, 3, 3, 3]
```
### f. Objects
##### I. Challenge
1. URL: https://edabit.com/challenge/5qYYauQwYwxz3nd9R
2. Solutions: https://www.dropbox.com/s/rgwvcn68qo68cx5/freeShipping.png?dl=0
##### II. Challenge
1. URL: https://edabit.com/challenge/5Yt2CrYdrJvoJFHRt
2. Solutions: https://www.dropbox.com/s/z1agitk025q3lpv/mapping.png?dl=0
### g. Classes
##### I. Challenge
1. URL: https://edabit.com/challenge/Hgb38yhWGwJCMHbRQ
2. Code:
```javascript
class Rectangle {
  constructor(sideA,sideB){
    this.sideA = sideA;
    this.sideB = sideB;
  }
  getArea(){return this.sideA*this.sideB};
  getPerimeter(){return (this.sideA + this.sideB) *2 };
}


class Circle {
	constructor(r){
    this.r = r;
  }
  
  getArea(){return Math.PI * this.r * this.r}
  getPerimeter(){return 2 * Math.PI * this.r}
}

let q = new Circle(4.44);
```
##### II. Challenge
1. URL: https://edabit.com/challenge/9zwdrfW99zmdRhibi
2. Code:
```javascript
class OnesThreesNines{
	constructor(n){
		this.ones = Math.floor(n / 1);
		this.threes = Math.floor(n / 3);
		this.nines = Math.floor(n / 9);
	}
}
```
