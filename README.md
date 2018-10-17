创建项目：
create-react-app counter-app
打开项目：
cd counter-app/
npm start
安装bootstrap
npm i bootstrap@4.1.1

初始化建造JSX（simple react snippets）：
imrc
cc
sfc
JSX需要注意：
ctrl +D 同时编辑
js要用{}
className代替class

let and const
`const` means that the identifier can’t be reassigned. 
let` tends to be for loops or mathematical algorithms

map method:  * Returns the elements of an array that meet the condition specified in a callback function.



what is an arrow function?
void having to type the function keyword, return keyword 
// (param1, param2, paramN) => expression

// ES5
var multiplyES5 = function(x, y) {
  return x * y;
};

// ES6
const multiplyES6 = (x, y) => { return x * y };
const multiplyES6 = (x, y) => x * y;

Parentheses are required when no parameters are present.
var docLogEs6 = () => { console.log(document); };

const prices = smartPhones.map(smartPhone => smartPhone.price);
const divisibleByThrreeES6 = array.filter(v => v % 3 === 0);


 {this.state.tages.length === 0 && "Please create a new tag!"}
 true&&'hi'&&1 返回1
 

 using arrow function replace constructor
 this.setState(); 把数据传输到view
 
 this.props 传输接受数据，function 但是read only
 
