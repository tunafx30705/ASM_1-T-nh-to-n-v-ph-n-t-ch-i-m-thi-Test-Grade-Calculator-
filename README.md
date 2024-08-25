
# Test Grade Calculator

Đây là dự án cung cấp tập lệnh Python để chấm điểm bài kiểm tra của học sinh dựa trên câu trả lời của họ và đáp án được xác định trước. Tập lệnh đọc dữ liệu đầu vào từ một tệp văn bản chứa câu trả lời của học sinh, xác thực dữ liệu, tính điểm và tạo báo cáo.


## Features

- Xác thực đầu vào (Input Validtion): Tập lệnh xác thực ID học sinh và tính đầy đủ của phiếu trả lời.
- Tính điểm (Score Calculation): Mỗi câu trả lời đúng được cộng 4 điểm, trả lời sai bị trừ 1 điểm, không có câu trả lời nào bị tính 0 điểm.
- Báo cáo chi tiết (Detailed Reporting): Cung cấp báo cáo về tổng số dữ liệu hợp lệ và không hợp lệ, số liệu thống kê tóm tắt và phân tích các lỗi phổ biến.
- Đầu ra tệp (File Output): Xuất ra tệp văn bản chứa mã số học sinh và điểm số tương ứng của chúng.



## Requirement
- Python 3.x
- Pandas
- Numpy
## Installation
Để chạy tập lệnh cục bộ, hãy làm theo các bước sau
1. **Sao chép kho lưu trữ (repository)**
```bash
  git clone https://github.com/tunafx30705/ASM_1-Test-Grade-Caculator.git
```
2. **Điều hướng đến thư mục dự án**
```bash
  cd ASM_1-Test-Grade-Caculator
```
3. **Đảm bảo Python và các thư viện cần thiết đã được cài đặt**
```bash
  pip install pandas numpy
```
## Usage/Examples

Để sử dụng tập lệnh để chấm điểm một lớp:
1. **Chuẩn bị tập tin đầu vào**: 
- Chuẩn bị một file định dạng txt có chứa ID sinh viên và câu trả lời của họ.
- File phải có ID của mỗi học sinh bắt đầu bằng "N", theo sau là 8 chữ số và tệp chứa chính xác 26 giá trị trên mỗi dòng (bao gồm cả ID học sinh). Dữ liệu đầu vào phải giống như ví dụ dưới đây:
```javascript
  N12345678,A,B,C,D,A,B,C,D,A,B,C,D,A,B,C,D,A,B,C,D,A,B,C,D,A,B
```
2. **Chạy tập lệnh**:
- Mở Notebook Jupyter `lastname_firstname_grade_the_exams.ipynb` để thực thi mã.
- Nhập tên file khi được nhắc. Ví dụ:
```javascript
  Enter a class file to grade (i.e., class1 for class1.txt): class1
```
3. **Đầu ra**:
- Tập lệnh tạo một tệp văn bản mới có tên `{class__grades.txt` chứa ID sinh viên và điểm số tương ứng của họ.
- Tập lệnh cũng xuất ra nhiều số liệu thống kê và phân tích khác nhau tới bảng điều khiển.


## License

Dự án này được cấp phép theo Giấy phép MIT - xem [Giấy phép MIT](https://choosealicense.com/licenses/mit/) để biết chi tiết.

