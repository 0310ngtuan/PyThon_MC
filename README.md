# PyThon_MC


MỘT SÓ PHƯƠNG THỨC PHỔ BIẾN TRONG MODULE OS

Module os trong Python cung cấp các phương thức để làm việc với hệ điều hành (Operating System). Dưới đây là một số phương thức phổ biến của module os:

os.getcwd(): Trả về đường dẫn thư mục làm việc hiện tại.
os.listdir(path='.'): Trả về danh sách tên các tệp và thư mục trong thư mục được chỉ định bởi đường dẫn path. Nếu path không được chỉ định, phương thức sẽ trả về danh sách các tệp và thư mục trong thư mục làm việc hiện tại.
os.mkdir(path, mode=0o777, *, dir_fd=None): Tạo một thư mục mới với đường dẫn path. Tham số mode là quyền truy cập cho thư mục mới được tạo. Giá trị mặc định là 0o777 (quyền truy cập rộng rãi nhất).
os.remove(path): Xóa tệp với đường dẫn path.
os.rename(src, dst): Đổi tên hoặc di chuyển tệp hoặc thư mục từ src sang dst.
os.path.join(path1[, path2[, ...]]): Tạo một đường dẫn bằng cách kết hợp các chuỗi path1, path2, ... với nhau và thêm ký tự phân cách đường dẫn thích hợp để tạo ra một đường dẫn hợp lệ trên hệ điều hành hiện tại.
os.path.exists(path): Kiểm tra xem đường dẫn path có tồn tại hay không.
os.path.isfile(path): Kiểm tra xem đường dẫn path có phải là tệp hay không.
os.path.isdir(path): Kiểm tra xem đường dẫn path có phải là thư mục hay không.
os.path.basename(path): Trả về tên tệp hoặc thư mục từ đường dẫn path.
os.path.dirname(path): Trả về đường dẫn thư mục cha của đường dẫn path.
os.path.abspath(path): Trả về đường dẫn tuyệt đối của path.
Các phương thức trên chỉ là một số ví dụ về cách sử dụng module os. Module này còn cung cấp rất nhiều phương thức khác để làm việc với hệ điều hành. Bạn có thể đọc thêm tài liệu chính thức của Python để biết thêm chi tiết.
