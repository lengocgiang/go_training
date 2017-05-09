# Go lang (chap 1)

```go
package main
import (
  "fmt"
)
// this is comment
func main() {
  fmt.Println("Hello World")
}
```

Một đoạn code chương trình Go được thực hiện từ trên xuống dưới, từ trái qua phải.


```go
package main
```

Dòng đầu tiên *package main* đây là câu lệnh khai "gói", tất cả chương trình Go đều được bắt đầu bằng câu lệnh khai báo goi. Tính năng gói sẽ cho phép chúng ta tái sử dụng code dễ dàng hơn.

Khi biên dịch Go có 2 loại 
* Biên dịch chương trình chạy trực tiếp(excutable)
* Biên dịch thành thư viện

```go
import ("fmt")
  ```
Sau dòng khai báo gói là dòng khai báo các gói chúng ta sẽ sử dụng. Ở đây là *import "fmt"*  (fmt viết tắt của Format) là gói code thực hiện định dạng dữ liệu vào/ra.

```go
//this is comment
```
tiếp theo là dòng comment, trong Go sử dụng 2 dấu *//* để viết comment.

Tiếp theo là phần khai báo hàm

```go
func main() {
  fmt.Println("Hello World")
  ```
  Tất cả các hàm trong Go đêu được định nghĩa bởi từ khoá *func* 
  theo sau là tên hàm(chúng ta sẽ có quy tắc đặt tên hàm ở sau),
  tiếp theo là cặp dấu (), bên trong cặp dấu này chúng ta có thể khai báo thêm tham số, nhưng ở trong hàm main thì không cần khai báo tham số.

  * Ngoài ra tên *main* là một tên đặc biệt, hàm main sẽ được gọi tự động gọi đến đầu tiên khi chạy từ một file thựcc thi.

  Bên trong hàm main chúng ta có một câu lệnh. Câu lệnh này có 3 phần, câu lệnhn ày gọi hàm Println trong gói fmt, hàm này nhận một tham số kiểu string. In ra chuỗi "Hello World". Println là viết tắt của print line nghĩa là in ra chuỗi trên màn hình.




