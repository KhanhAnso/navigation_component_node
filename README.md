# navigation_component_node

1.setupActionBarWithNavController
- Thiết lập Thanh hành động được trả về AppCompatActivity.getSupportActionBarđể sử dụng với NavController.
- Bằng cách gọi phương thức này, tiêu đề trong thanh tác vụ sẽ tự động được cập nhật khi điểm đến thay đổi (giả sử có giá trị hợp lệ label).
- Điểm đến bắt đầu của biểu đồ điều hướng của bạn được coi là điểm đến cấp cao nhất duy nhất.
- Trên điểm đến bắt đầu của biểu đồ điều hướng của bạn, Thanh tác vụ sẽ hiển thị biểu tượng ngăn kéo nếu bố cục Có thể mở đã cho không rỗng.
- rên tất cả các điểm đến khác, ActionBar sẽ hiển thị nút Lên. Gọi navigateUp để xử lý nút Lên.


2.setupWithNavController
- Thiết lập một Toolbar để sử dụng với một NavController.
- Bằng cách gọi phương thức này, tiêu đề trong Thanh công cụ sẽ tự động được cập nhật khi điểm đến thay đổi (giả sử có giá trị hợp lệ label).
- Điểm đến bắt đầu của biểu đồ điều hướng của bạn được coi là điểm đến cấp cao nhất duy nhất. 
- Trên điểm đến bắt đầu của biểu đồ điều hướng của bạn, Thanh công cụ sẽ hiển thị biểu tượng ngăn kéo nếu bố cục Có thể mở đã cho không rỗng.
- Trên tất cả các điểm đến khác, Thanh công cụ sẽ hiển thị nút Lên.
- Phương thức này sẽ gọi navigateUp khi nhấp vào nút Điều hướng.


3.navigateUp
- Xử lý nút Lên bằng cách ủy quyền hành vi của nó cho NavController đã cho.

4.
