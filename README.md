function isEven (number) {
    let flag = false;
    while (number >=0) {
        flag = !flag;
        number--;
    } 
    return flag;
}

console.log(isEven(5));
console.log(isEven(10));
console.log(isEven(-6));

//not allowed to use the modulus operator (%) nor the division operator (/).
