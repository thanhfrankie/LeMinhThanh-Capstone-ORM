# Vũ Lê Bảo Long

-   POST trang đăng ký
    -   http://localhost:6969/api/v1/user/register
-   POST trang đăng nhập
    -   http://localhost:6969/api/v1/user/login
-   GET danh sách ảnh về
    -   http://localhost:6969/api/v1/image/list 
        -   if have token: get list images with value saved of user
        -   if haven't token: get list images without value saved
-   GET tìm kiếm danh sách ảnh theo tên
    -   http://localhost:6969/api/v1/image/search?searchText=t
-   GET thông tin ảnh và người tạo ảnh bằng id ảnh
    -   http://localhost:6969/api/v1/image/image-info/10
-   GET thông tin bình luận theo id ảnh
    -   http://localhost:6969/api/v1/image/comment/10

# Nguyễn Thị Huỳnh Nhi

-   GET thông tin đã lưu hình này chưa theo id ảnh
    -   http://localhost:6969/api/v1/image/image-info/1 (need to provide tokens)
-   POST lưu thông tin bình luận của người dùng với hình ảnh
    -   http://localhost:6969/api/v1/image/comment
-   GET thông tin user
    -   http://localhost:6969/api/v1/user
-   GET danh sách ảnh đã lưu theo user id
    -   http://localhost:6969/api/v1/user/images-created
-   GET danh sách ảnh đã tạo theo user id
    -   http://localhost:6969/api/v1/user/images-saved
-   DELETE xoá ảnh đã tạo theo id
    -   http://localhost:6969/api/v1/image/delete/1
-   PUT chỉnh sửa thông tin cá nhân của user
    -   http://localhost:6969/api/v1/user/update
