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

> 7.1 - Class fields are public by default, but private class members can be created by using a hash # prefix. The privacy encapsulation of these class features is enforced by JavaScript itself.
>
> > (Vietnamese: Các trường lớp là công khai theo mặc định, nhưng các thành viên lớp riêng tư có thể được tạo bằng cách sử dụng tiền tố băm #. Việc đóng gói quyền riêng tư của các tính năng lớp này được thực thi bởi chính JavaScript.)

> Private members are not native to the language before this syntax existed. In prototypical inheritance, its behavior may be emulated with WeakMap objects or closures, but they can't compare to the # syntax in terms of ergonomics.
>
> > (Vietnamese: Các thành viên riêng tư không có nguồn gốc từ ngôn ngữ trước khi cú pháp này tồn tại. Trong kế thừa nguyên mẫu, hành vi của nó có thể được mô phỏng bằng các đối tượng WeakMap hoặc bao đóng, nhưng chúng không thể so sánh với cú pháp # về mặt công thái học.)

```js
class ClassWithPrivate {
  #privateField; // (1) - Private fields
  #privateFieldWithInitializer = 42;

  #privateMethod() {
    // (2) - Private methods
  }

  static #privateStaticField; // (3) - Private static fields
  static #privateStaticFieldWithInitializer = 42;

  static #privateStaticMethod() {
    // (4) - Private static methods
  }

  // (5) -  Private getters
  // (6) -  Private setters
  // (7) -  Private static getters
  // (8) -  Private static setters
}

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #8 - `CONSTANT NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN CONSTANT` TRONG JS)

> 8.1 - Last but not least, constants - which aim to be immutable variables - in JavaScript are written in capital letters (UPPERCASE):
>
> > (Vietnamese: Cuối cùng nhưng không kém phần quan trọng, các hằng số - nhằm mục đích là các biến không thay đổi - trong JavaScript được viết bằng chữ in hoa (UPPERCASE):)

```js
const SECONDS = 60;
const MINUTES = 60;
const HOURS = 24;

const DAY = SECONDS * MINUTES * HOURS;

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

> 8.2 - If a constant has more than one word in its variable declaration name, it uses underscores (\_) to separate the words:
>
> > (Vietnamese: Nếu một hằng số có nhiều hơn một từ trong tên khai báo biến của nó, nó sẽ sử dụng dấu gạch dưới (\_) để phân tách các từ:)

```js
const DAYS_UNTIL_TOMORROW = 1;

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

#### #9 - `GLOBAL VARIABLE NAMING` CONVENTION(QUY ƯỚC ĐẶT `TÊN GLOBAL VARIABLE` TRONG JS)

> 9.1 - A JavaScript variable is defined as a Global variable, if all its contexts have access to it.
>
> Often the context is defined by the JavaScript file where the variable is declared/defined, but in smaller JavaScript projects it can be the entire project.
>
> And there is no special naming convention for global variables in JavaScript.
>
> A global JavaScript variable declared at the top of the project/file.
> A global JavaScript variable is written in camelCase if it is mutable.
> A global JavaScript variable is written in UPPERCASE if it is immutable.
>
> > (Vietnamese: Một biến JavaScript được xác định biến Global (toàn cục), nếu trong tất cả ngữ cảnh của nó đều có quyền truy cập vào nó.
>
> > Thường thì ngữ cảnh được xác định bởi tệp JavaScript nơi biến được khai báo / định nghĩa, nhưng trong các dự án JavaScript nhỏ hơn, nó có thể là toàn bộ dự án.
>
> > Và cũng không có quy ước đặt tên đặc biệt nào cho các biến toàn cục trong JavaScript.
>
> > Một biến JavaScript toàn cục được khai báo ở đầu dự án / tệp.
> > Một biến JavaScript toàn cục được viết bằng camelCase nếu nó có thể thay đổi được.
> > Biến JavaScript toàn cục được viết bằng UPPERCASE nếu nó là bất biến.)

#### #10 -`FILE NAMING` CONVENTION( QUY ƯỚC ĐẶT `TÊN FILE` TRONG JAVASCRIPT)

> 10.1 - There are two file naming strategies in JavaScript: PascalCase and kebab-case.
>
> In Front end applications, you will often find people using the PascalCase style to name components (e.g. React components).
>
> > (Vietnamese: Có hai chiến lược đặt tên tệp trong JavaScript: PascalCase và kebab-case.
>
> > Trong các ứng dụng Front end, bạn sẽ thường thấy người ta sử dụng kiểu PascalCase để đặt tên cho các component (ví dụ: các component của React).)

```js
- components/
--- user/
----- UserProfile.js
----- UserList.js
----- UserItem.js
--- ui/
----- Dialog.js
----- Dropdown.js
----- Table.js

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

> 10.2 - In contrast, in a back end application, kebab-case is the usual usage:
>
> > (Vietnamese: Ngược lại, trong ứng dụng back end, kebab-case là cách sử dụng thông thường:)

```js
- routing/
--- user-route.js
--- messages-route.js

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

> 10.3 - You will also see someone using camelCase, but similar in front end applications. But this runs the risk that the operating system is handling them in a different way which could lead to errors.
>
> That's why the kebab-case style should be the standard for file naming in JavaScript.
>
> > (Vietnamese: Bạn cũng thể sẽ thấy ai đó sử dụng camelCase, nhưng tương tự như trong các ứng dụng front end. Nhưng điều này có nguy cơ là hệ điều hành đang xử lý chúng theo cách khác có thể dẫn đến lỗi.
> >
> > Đó là lý do tại sao kiểu kebab-case nên là tiêu chuẩn cho việc đặt tên tệp trong JavaScript.)

#### `(*)` - SHOULD BE USE `underscores_naming` for variable names?

> So is underscore used for naming in JavaScript?
>
> Since camelCase and PascalCase are mostly considered in JS, you've seen that underscores are rarely used for private variables or constants.
>
> Sometimes you'll find an underscore when receiving information from a third party like a database or an API.
>
> Another case where you may see underscores are unused function parameters.
>
> > (Vietnamese: Vậy còn dấu gạch dưới có được sử dụng để đặt tên trong JavaScript không?
> >
> > Vì camelCase và PascalCase chủ yếu được xem xét trong JS, bạn đã thấy rằng dấu gạch dưới hiếm khi được sử dụng cho các biến hoặc hằng số riêng.
> >
> > Đôi khi, bạn sẽ tìm thấy dấu gạch dưới khi nhận thông tin từ bên thứ ba như cơ sở dữ liệu hoặc API.
> >
> > Một trường hợp khác mà bạn có thể thấy dấu gạch dưới là các tham số hàm không được sử dụng.)

#### `(*)` - ? SHOULD BE USE `HYPHEN-NAMING` TO NAME VARIABLES?

> Using hyphen for JavaScript names is also not common. It just makes things more difficult.
>
> For example when using them in object orientation:
>
> > (Vietnamese: Sử dụng dấu gạch ngang để đặt tên JavaScript cũng không phải là phổ biến. Nó chỉ làm cho mọi thứ trở nên khó khăn hơn.)
> >
> > Ví dụ như khi sử dụng chúng trong hướng đối tượng:

```js
var person = {
  "first-name": "Mai", // 👎
  "last-name": "Hà", // 👎
};

var firstName = person["first-name"]; // 👎

var person = {
  firstName: "Mai", // 👍
  lastName: "Hà", // 👍
};

var firstName = person.firstName; // 👍

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```

> And you can't even use hyphen for variable declarations directly:
>
> > (Vietnamese: Và thậm chí bạn không thể sử dụng trực tiếp dấu gạch ngang cho khai báo biến:)

```js
var first-name = 'Mai';
// Uncaught SyntaxError: Unexpected token '-'

// P.S 👨🏻‍💻 I always need your contribute. Let's take the code better!
```
