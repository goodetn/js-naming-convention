# # - JAVASCRIPT NAMING CONVENTION(`QUY ƯỚC ĐẶT TÊN TRONG JAVASCRIPT`)

#### #1 - `VARIABLE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN BIẾN` TRONG JS)

> 1.1 - JavaScipt variables are case sensitive. Therefore, JavaScript variables with lowercase and uppercase characters are different.
>
> > (Vietnamese: Các biến JavaScipt phân biệt chữ hoa chữ thường. Do đó, các biến JavaScript với ký tự viết thường và viết hoa là khác nhau)

```js
const intro = "Hello world!";

const Intro = "My name Peter";

const INTRO = "I'm from Vietnam";

console.log(intro);
// "Hello world!"

console.log(Intro);
// "My name Peter"

console.log(INTRO);
// "I'm from Vietnam"

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

> 1.2 - JavaScript variables must describe what they mean. It is not necessary to add a comment for an additional description of the variable:
>
> > (Vietnamese: Biến JavaScript phải tự mô tả ý nghĩa của nó. Không cần thiết phải thêm nhận xét để có mô tả bổ sung cho biến)

```js
const str = "Hello world!"; // 👎

const title = "My name Peter"; // 👍
```

> 1.3 - Constants, regular variables (types in use):
>
> > (Vietnamese: Hằng số, biến thông thường(kiểu đang dùng))

```js
// constant:
const MAX_LENGTH = 30; // 👍

// normal variable:
let currentValue = 1; // 👍

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #2 - `BOOLEAN NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN BOOLEAN` TRONG JS)

> 2.1 - Adding a prefix like `is`, `are` or `has` is the simplest way to help any programmer using JavaScript to distinguish a boolean variable from another variable.:
>
> > (Vietnamese: Thêm tiền tố như `is`, `are` hoặc `has` là cách đơn giản nhất giúp mọi lập trình viên sử dụng JavaScript phân biệt biến boolean với một biến khác.)

```js
var mobile = true; // 👎

var isMobile = true; // 👍

var difference = false; // 👎

var areDifference = false; // 👍

var title = true; // 👎

var hasTitle = true; // 👍

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #3 - `FUNCTION NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN FUNCTION` TRONG JS)

> 3.1 - JavaScript functions are also written in camelCase style. Also, the best way to really tell what a function is doing is to use a verb as a prefix to the function name:
>
> > (Vietnamese: Các hàm JavaScript cũng được viết theo kiểu camelCase. Ngoài ra, cách tốt nhất để thực sự cho biết hàm đang làm gì là sử dụng một động từ làm tiền tố cho tên hàm)

```js
// name 👎
function name(firstName, lastName) {
  return `${firstName} ${lastName}`;
}

// getName 👍
function getName(firstName, lastName) {
  return `${firstName} ${lastName}`;
}

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #4 - `CLASS NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN CLASS` TRONG JS)

> 4.1 - A class in JavaScript is declared using the PascalCase type as opposed to other JavaScript data structures:
>
> > (Vietnamese: Một lớp trong JavaScript được khai báo bằng kiểu PascalCase trái ngược với các cấu trúc dữ liệu JavaScript khác)

```js
class Post {
  constructor(title, slug) {
    this.title = title;
    this.slug = slug;
  }
}

const post = new Post("Javascript learning", "javascript-learning");

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #5 - `COMPONENT NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN COMPONENT` TRONG JS)

#### #6 - `METHOD NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN MEDTHOD` TRONG JS)

#### #7 - `PRIVATE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN PRIVATE` TRONG JS)

#### #8 - `CONSTANT NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN CONSTANT` TRONG JS)

#### #9 - `GLOBAL VARIABLE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN GLOBAL VARIABLE` TRONG JS)

#### #10 -`FILE NAMING` CONVENTION( QUY ƯỚC ĐẶT `TÊN FILE` TRONG JAVASCRIPT)
