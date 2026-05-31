# PBT_08 - Bài tập JavaScript

* Function Declaration, Function Expression, Arrow Function
* Closure
* `var`, `let` và hoisting
* Array methods: `map`, `filter`, `reduce`, `sort`, `find`
* Object destructuring và spread operator
* Higher-order functions
* Shopping cart sử dụng closure
* Quản lý sản phẩm E-Commerce

## Danh sách file bài tập

| File     | Nội dung     |
| ------- | -------- |
| `a2.js`              | Closure, counter, so sánh `var` và `let` trong `setTimeout`    |
| `product_manager.js` | Quản lý sản phẩm E-Commerce bằng array methods                 |
| `shopping_cart.js`   | Giỏ hàng sử dụng closure, không dùng class                     |
| `higher_order.js`    | Higher-order functions: `pipe`, `memoize`, `debounce`, `retry` |
| `answer.md`          | Ghi chú, giải thích và câu trả lời lý thuyết                   |

## Mô tả các bài chính

### Bài B1 - Quản lý sản phẩm E-Commerce

File: [`product_manager.js`](./product_manager.js)

Các chức năng chính:

* Lọc sản phẩm còn hàng
* Lọc sản phẩm theo category và khoảng giá
* Sắp xếp sản phẩm theo giá tăng/giảm
* Tìm sản phẩm rẻ nhất theo từng category
* Tính tổng giá trị kho
* Format danh sách sản phẩm
* Tính rating trung bình
* Tìm kiếm sản phẩm theo keyword

### Bài B2 - Shopping Cart

File: [`shopping_cart.js`](./shopping_cart.js)

Các chức năng chính:

* Thêm sản phẩm vào giỏ hàng
* Xóa sản phẩm theo `id`
* Cập nhật số lượng sản phẩm
* Tính tổng tiền
* Áp dụng mã giảm giá: `SALE10`, `SALE20`, `FREESHIP`
* In giỏ hàng dạng bảng
* Lấy tổng số lượng sản phẩm
* Xóa toàn bộ giỏ hàng

### Bài B3 - Higher-Order Functions

File: [`higher_order.js`](./higher_order.js)

Các hàm đã xây dựng:

* `pipe()` — nối chuỗi nhiều function
* `memoize()` — lưu cache kết quả đã tính
* `debounce()` — chỉ chạy hàm sau khi người dùng ngừng gọi liên tục
* `retry()` — thử lại hàm async nếu bị lỗi
  
Các bài tập trong repository này tập trung vào việc luyện tập JavaScript hiện đại, đặc biệt là cách sử dụng arrow function, closure, array methods và higher-order functions để viết code ngắn gọn, dễ đọc và dễ bảo trì hơn.
