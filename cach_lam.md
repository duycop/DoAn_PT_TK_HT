# CÁCH LÀM BÀI: 

## TUỲ THEO ĐỀ TÀI MÀ NỘI DUNG SẼ KHÁC NHAU, NHƯNG FORMAT CHUNG SẼ LÀ:

### BÌA ĐỒ ÁN: Chứa tên môn, tên sv, tên đề tài, tên gv hướng dẫn.
### PHIẾU GIAO ĐỀ TÀI+NHẬN XÉT GVHD, GV CHẤM: (Phải chú ý cái này BUỘC phải có trước khi đóng quyển)
### LỜI CẢM ƠN: (ít nhất 1/3 trang A4, nên làm cuối cùng trước khi đóng quyển để biết cảm ơn ai)
### MỤC LỤC: (tự động)
  - ...
  - ...
### Chương 1. Khảo sát: 
  - (Càng dài càng tốt, khoảng 5-10 trang) 
  - Trình bày hiện trạng hệ thống cũ : hiện trạng, cách xử lý thông tin, các biểu mẫu, luồng dữ liệu hiện tại, 
  -  khâu nào là con người dùng thủ công, khâu nào là dùng excel or phần mềm khác
### Chương 2. Phân tích: 
  - (Càng chi tiết càng tốt) 
  - khâu nào sẽ cải tiến, 
  - khâu nào giữ nguyên, 
  - việc cải tiến sẽ thay đổi quy trình như thế nào? 
  - ai được hưởng lợi, có nhanh hơn ko, có chính xác hơn không.
### Chương 3. Thiết kế: 
  - (Ưu tiên tối ưu lưu trữ, 3nf, ràng buộc dữ liệu, ko dư thừa, ko mất mát thông tin, tiện cho tra cứu, tìm kiếm và thống kê)
  - Đưa ra Mô hình CSDL, tên bảng (s), tên trường của từng bảng. Mối quan hệ giữa các bảng.
  - Phân tích cái nào là khoá chính, khoá ngoại, các điều kiện ràng buộc cứng của 1 trường, các điều kiện khác liên đới tới các bảng khác,...
### Chương 4. Thực hiện: 
  - (Càng chụp nhiều ảnh quá trình làm + hướng dẫn: càng tốt, càng chứng tỏ mình làm thật, mình hiểu vấn đề)
  #### 4.1. Xây dựng CSDL (làm trên sql server 2022): 
  - Tạo DB, tạo các tables,.. bằng thao tác trên giao diện đồ hoạ ==> chụp ảnh quá trình làm. 
  - Tạo các script sql tương đương với quá trình đồ hoạ trên.
  #### 4.2. Xây dựng các kịch bản ứng với các chức năng: 
  - VẼ SƠ ĐỒ LUỒNG DỮ LIỆU CHO MỖI CHỨC NĂNG 
  - VIẾT SP_ (Store Procedure) để thực hiện việc xử lý thông tin như sơ đồ
  #### 4.3. Tạo Project Web  app / Project Windows App: 
  - Có giao diện phù hợp với các chức năng đã thiết kế.     
  - Phần backend xử lý :       
    - Lấy data trên form      
      - tiền xử lý       
      - gọi SP để xử lý dữ liệu (sẽ thay đổi data trong db)       
      - lấy kq xử lý       
      - hậu xử lý       
      - hiển thị lên giao diện
  #### 4.4. Cài đặt và kiểm thử: 
  - Chụp giao diện làm việc,     
  -  kết quả nhập xuất báo cáo,...
### Chương 5. Kết luận (mạnh dạn nói tôi hiểu và ứng dụng đc cái gì, và cũng thẳng thắn thừa nhận những thứ chưa tốt: càng chứng tỏ bạn hiểu vấn đề)
  - Đánh giá các kết quả đã làm được: nắm được kỹ thuật gì, vận dùng nó làm đc gì...
  - Nhận xét các điểm hạn chế: xấu, chưa phù hợp,.....
  - Nướng phát triển: .......
### TÀI LIỆU THAM KHẢO: (càng tham khảo nhiều càng tốt, trích dẫn phải đầy đủ và chi tiết)
[1] ...
[2] ...
