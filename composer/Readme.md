# Bài tập package 1
Tạo 1 package có tên structure-html dùng để viết lại cấu trúc html của nội dung trong file [doc html](doc.html) vs [doc html](doc_1.html)

**Mong mụốn:**
Viết lại nội dung của doc_1.html vs doc.html theo cấu trúc

**Ý tưởng viết lại**
- Loại bỏ hết các thẻ html ngoài br.
- Một câu văn có xu hướng kết thúc bằng dấu chấm (.) và xuống dòng thì có `\n`
- TRong đoạn văn mô tả thì mỗi một khối sẽ có tiêu đề như:
 
    - `Mô tả công việc`: công việc, description, mô tả công việc
    -  `Yêu cầu`: yêu cầu công việc, yêu cầu, requirement ...
    - `Quyền lợi`: quyền lợi được hưởng, quyền lợi, benefit, lợi ích, Chế độ

- Bắt đầu viết code. Đọc văn bản từ tren xuống dưới thu thập về một mảng đa chiều ..
- Lặp dữ liệu và tạo html ...

`GHi chú`: Trên đấy là ý tưởng để thực thi. Trong quá trình làm có thể phải theo dõi dữ liệu. Lên có thể phải xem lại
              
## Yêu cầu thêm
- Tên packages có dạng ten_ung_vien/structure-html
- Phải có Readme.md theo mẫu
- Cấu trúc dạng composer package
- Có phpunit test
- Submit lên packagist
