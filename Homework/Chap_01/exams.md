# BTVN buổi 1

Deadline bài 4 là 23h59 Thứ 7, còn 3 bài đầu là 12h00 Thứ 6 nhé mọi người.
Mọi người push code lên github và comment ở dưới post này.

### 1. Cách kiểm tra một biến x cho trước là function, array, number, string, undefined

### 2. Tìm hiểu về Event loop, giải thích tại sao đoạn code sau chữ Một lại hiện sau chữ Hai

```js
setTimeout(function () {
  console.log("Một");
}, 0);
function second() {
  console.log("Hai");
}
second();
```

### 3. Tìm hiểu về deep copy và shallow copy trong JS. Giải thích kết quả của đoạn code sau.

```js
const macbooks = ["macbook2015", { model: "macbook2014" }, "macbook2017"];
const apples = [...macbooks];
apples[0] = "air";
apples[1].model = "m1";
console.log(macbooks); // ['macbook2015', { model: 'm1' }, 'macbook2017']
console.log(apples); // ['air', { model: 'm1' }, 'macbook2017']
```

### 4. Thực hành JS, HTML, CSS làm một trang web todo list gồm các tính năng sau:

- Thêm công việc
- Đánh dấu hoàn thành
- Xoá công việc
