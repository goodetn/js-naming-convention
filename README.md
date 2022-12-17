# # - JAVASCRIPT NAMING CONVENTION(`QUY ƯỚC ĐẶT TÊN TRONG JAVASCRIPT`)

#### [#1](https://github.com/goodetn/js-naming-convention/blob/52b047c3d649344cb435c9001aade0093a26ca5b/README.md?plain=1#L3) - `VARIABLE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN BIẾN` TRONG JS)

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

#### [#2](https://github.com/goodetn/js-naming-convention/blob/f32ee30b4cc39f0ee205715b9c756b7ec37693c3/README.md?plain=1#L52) - `BOOLEAN NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN BOOLEAN` TRONG JS)

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

#### [#3](https://github.com/goodetn/js-naming-convention/blob/c4c4b906d4b9b42d8e95a4edd5be20b8450454a9/README.md?plain=1#L74) - `FUNCTION NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN FUNCTION` TRONG JS)

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

#### [#4](https://github.com/goodetn/js-naming-convention/blob/178e7ad6f16e1a6059a49d979b801b651acd14a6/README.md?plain=1#L94) - `CLASS NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN CLASS` TRONG JS)

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

#### [#5](https://github.com/goodetn/js-naming-convention/blob/b4f44b8f285ac92018e66a3316156130e7ba867f/README.md?plain=1#L113) - `COMPONENT NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN COMPONENT` TRONG JS)

> 5.1 - Components are commonly found in Frontend Frameworks like React, they are also widely declared with the PascalCase type:
>
> > (Vietnamese: Các component thường được tìm thấy trong các Frontend Framework như React, chúng cũng được khai báo rộng rãi với kiểu PascalCase)

```jsx
// post 👎
function post({ title, slug }) {
  return (
    <Link to={slug}>
      <h3>{title}</h3>
      <span>...</span>
    </Link>
  );
}

// Post 👍
function Post({ title, slug }) {
  return (
    <Link to={slug}>
      <h3>{title}</h3>
      <span>...</span>
    </Link>
  );
}

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### [#6](https://github.com/goodetn/js-naming-convention/blob/be5b482205315b9ebcdba7f0e87d95522bb14732/README.md?plain=1#L143) - `METHOD NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN METHOD` TRONG JS)

> 6.1 - Like JavaScript functions, a method name in a JavaScript class is declared with camelCase::
>
> > (Vietnamese: Giống như các hàm JavaScript, tên một phương thức trong một lớp JavaScript được khai báo với kiểu camelCase)

```js
class Post {
  constructor(title, slug) {
    this.title = title;
    this.slug = slug;
  }
  //   getTitle 👍
  getTitle() {
    return `🔗 ${this.title}`;
  }
}

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #7 - `PRIVATE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN PRIVATE` TRONG JS)

#### #8 - `CONSTANT NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN CONSTANT` TRONG JS)

#### #9 - `GLOBAL VARIABLE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN GLOBAL VARIABLE` TRONG JS)

#### #10 -`FILE NAMING` CONVENTION( QUY ƯỚC ĐẶT `TÊN FILE` TRONG JAVASCRIPT)
