MÔ HÌNH OSI LÀ GÌ ?
* là mô hình tham chiếu kết nối các hệ thống mở . dây là một thiết kế dựa vào nguyên lý tầng cấp lý giải 1 kỹ thuật kết nối truyền thông một cách trừu tượng giữa các máy vi tính và thiết kế giao thức mạng
* còn được gọi là mô hình 7 tầng
* mô hình gồm 7 tầng mô hình osi là hệ thống mở phải có khả năng liên kết với cac sheej thóng khác và tương thích với các chuẩn osi
*  quá trình các ứng dụng được xử lý trong hệ thống mở trong khi các hoạt động kết nối giữa các hệ thống vẫn được duy trì
*  thiết lập kênh logic đề nhằm mực đích thực hiện trao đổi thông tin giữa các thực thể

*  CÓ 2 LOẠI GIAO THỨC TRONG MÔ HÌNH OSI
*  giao thức liên kết ( connectinon-oriented)
*  các thực thể đồng tầng trong 2 hệ thống cần phải thiết lập 1 liên kết logic trươvs khi truyền dữ liệu
*  chúng thương lượng với nhau về tham số nên cắt hay bỏ dữ liệu
*  thiết lập logicj nhằm đảm bảo an toàn dộ tin cậy trong quá trình trao đổi dữ liệu
*  giao thức không liên kết (connectinonless)
*  thì dữ liệu sễ được truyền độc lập trên các tuyến khác nhau. chỉ có giai đoạn duy nhất truyền dữ liệu với các giao thức không liên kết

CHỨC NĂNG CỦA 7 TẦNG TRONG MÔ HÌNH OSI

* tầng vật lý (physical layer)
* là tầng thấp nhất trong mô hình 7 tầng lớp osi
* các thực thể giao tiêp với nhau  qua 1 đươcg truyền vật lý
* tầng vật lý xác định thủ tục,chức năng về điện,quang,cơ để kich hoạt và duy trì các kết nối vật lý giữa các hệ thống mạng
* cung cấp các cơ chế hàm,điện,thủ tục,.....nhằm kết nối các phần tủ mạng thành 1 hệ thống bằng các phương pháp vật lý đảm bảo các yêu cầu về chuyển mạch hoạt động tạo ra các dường truyền thực cho các chuỗi bit thông tin

* physical layer cũng có 2 loại : truyền dị bộ và truyền đòng bộ

*tầng liên kết dữ liệu (data link layer)
* thực hiện thiết lập liên kết duy trì hay hủy bỏ liên kết dữ liệu. Kiểm soát lỗi và kiểm soát lưu lượng

* tầng mạng ( netwwork layer )
* là quyết định xem dữ liệu sẽ đến máy nhận như thế nào lớp này nắm chắc các thành phần như viueecj xác định định tuyến địa chỉ và các giao thức logic
* lớp mạng này tạo các đường logic được biết đến như các mạch ảo giữa máy nguồn và máy 
* https://hdlink.vn/mo-hinh-osi-la-gi#:~:text=m%E1%BA%A1ng%20qu%E1%BA%A3ng%20b%C3%A1.-,Network%20Layer%20(t%E1%BA%A7ng%20m%E1%BA%A1ng),-Tr%C3%A1ch%20nhi%E1%BB%87m%20c%E1%BB%A7a

* tầng vận chuyển ( transport layer )
* là tầng cao nhất liên quan đến giao thức trao đổi dữ liệu giữa các hệ thống mở và kiểm soát được dữ liệu từ nút tới nút
* thực hiện chia các gói tin lớn thành các gói tin nhỏ và đánh số gói in theo thứ tự trước khi được gửi đi
* là thầng cuối cùng  chịu trách nhiệm về mức độ an toàn trong truyền dữ liệu nên phụ thuộc nhiều vào bản chất tầng mạng
* tầng vận chuyên cũng cõ thể thực hiện việc ghép kênh mội vài liên kết vào cùng 1 để giảm giá thành

* tầng phiên (session layer )
* cho phép người dùng đến các máy tính khác nahu thiết lập duy trì và đồng bộ phiên truyền thông giữa họ với nhau
* nghĩa là tầng phiên thiết lập các giao dịch giữa các thực thể đầu  


