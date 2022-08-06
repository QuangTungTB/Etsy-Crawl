# Etsy47-Etsy-Crawler-LTS
*Note: 
- Phần mềm là file rar trong file được tải về.
- Đảm bảo cập nhật chromedriver.exe trùng với phiên bản chrome đang dùng được cài trên máy, cập nhật chromedriver.exe mới nhất tại https://chromedriver.chromium.org/downloads phiên bản cho win32. Tải chromedriver về, giải nén và replace vào thư mục chứa tool.
- Từ bản 3.0.0 trở đi cần có plugin "JSON Basic Authentication" để dùng tính năng chuyển đổi size ảnh đầu ra, link tại tại https://github.com/WP-API/Basic-Auth .
- Bản ổn định hiện tại: v3.0.2

*Bản 3.1.1:
- Tối ưu hoá luồng chạy.
- Sửa lỗi hệ thống.

*Bản 3.0.2:
- Sửa lỗi hệ thống.
- Tăng cường bảo mật.

*Bản 3.0.0:
- Thêm chức năng tự động chuyển đổi ảnh đầu ra về size nhất định.
- Tự động thêm ảnh nền cho ảnh được chuyển đổi (nếu được chọn).

*Bản 2.21.5:
- Fix lỗi chrome 103.0.5060.114  .wt-text-title.

*Bản 2.21.4:
- HOT FIX Sửa lỗi bộ lọc không nhận sản phẩm nào khi cào bằng link.

*Bản 2.21.3:
- Sửa lỗi không lưu lại mật khẩu lần đăng nhập trước đó.

*Bản 2.21.2:
- Thay đổi link sản phẩm từ sku thành tên sản phẩm.

*Bản 2.21.1:
- Sửa lỗi mất mô tả khi up sản phẩm trong những lần chạy sau khi mở lại tool đã được tắt trước đó.

*Bản 2.21.0:
- Sửa lỗi hệ thống.
- Thêm tính năng tự động lấy tags từ etsy cho từng sản phẩm.

*Bản 2.20.0:
- Hệ thống đăng nhập và bảo mật bằng bằng tài khoản Twobros.
- Sửa lỗi hệ thống

*Bản 2.19.0.1:
- Tính năng tìm theo link trang đã có thể tìm theo số lượng trang cài đặt.

*Bản 2.18.1:
- Cập nhật hướng dẫn.
- Thêm tính năng tìm theo link trang.
- Cập nhật thông báo chi tiết lỗi khi kết nối với chrome.https://github.com/WP-API/Basic-Auth

*Bản 1.0.0:
- Cào sản phẩm từ etsy theo từ khóa, tên shop trong trang bán hàng hoặc lịch sử bán hàng.
- Có bộ lọc sản phẩm theo lượng review của sản phẩm (*lượng review sản phẩm không phải lượng review cửa shop) và theo trạng thái bestseller (bestseller và popular now là tương đương).
- Tự động đẩy sản phẩm chứa tên, sku (id sản phẩm của etsy), mô tả (có thể custom), tag, giá (có thể custom), giá discount (có thể custome) và danh mục lên trang Woocommerce đã cài đặt trước đó.
- Lưu lại thông tin dùng để chỉnh sửa cho những lần đăng nhập sau.
