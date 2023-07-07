thông tin chung dataset:
- name: 300 món ăn Việt Nam
- author: Nguyễn Thượng Hoàng Long - VCCorp Đà Nẵng 2023
- email: 
	longnguyenthuonghoang@tech.admicro.vn
	longbuonte@gmail.com
- date: tháng 7/2023
- version: 1.0 (base)
- original target: fewshot retrieval - fewshot classificate (cho image-text transformer models như CLIP)

thông tin statitics:
- mỗi class khoảng 12-55 image
- tùy vào độ đa dạng của định nghĩa class theo hình ảnh mà sẽ có nhiều hoặc ít image trong class hơn
- trung bình mỗi class có 20 image (default)
- chi tiết các class tại danh_sach.xlsx
- tên class theo tiếng việt có dấu, các âm phân cách bằng _
- đã cố gắng loại bỏ các class có định nghĩa gần nhau về hình ảnh
- cố gắng xây dựng phân biệt cấu trúc nhận dạng theo cách dễ dàng

thông tin image:
- cố gắng giữ được hoàn chỉnh kích thước gốc khi crawl
- chỉ có .png / .jpg , loại bỏ .gif và .html
- tên theo form: [class_name]_[2 digits numero].[jpg/png]
