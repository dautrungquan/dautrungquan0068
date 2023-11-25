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

* tầng trình bày (presentation)
* giải quyết các vấn đề liên quan ddeesn ngữ nghĩa và cú pháp của thông tin được truyền đi
* biểu diễ thông tin phù hơp với thông tin người dùng và ngược lại
* tầng trình bày có trách nhiệm chuyển đổi dữ liệu  gửi đi trên mạng từ 1 loại biểu diễn này sang biểu diễn khác
* tầng trình bày cung cấp 1 dạng biểu diễn truyền thông chung cho phép chuyển đổi sang bộ biểu diễn chung từ biểu diễn cục bộ và ngược lại

* tầng ứng dụng (appliccation layer)
* hỗ trợ ứng dụng và các tiến trình  có liên quan đến người sự dụng cuối
* tại lớp này chất lượng được phục vụ đối tác truyền thông xác thực người dùng quyền riêng tư hay bất kì ràng buộc nào về cú pháp dữ liệu sẽ được xem sét và quyết định
* cung cấp các dịch vụ ứng dụng chop truyền email ,file hay các phần mềm dịch vụ khác
* https://hdlink.vn/mo-hinh-osi-la-gi#:~:text=v%C3%A0%20ng%C6%B0%E1%BB%A3c%20l%E1%BA%A1i.-,Application%20Layer%20(t%E1%BA%A7ng%20%E1%BB%A9ng%20d%E1%BB%A5ng),-Application%20Layer%20l%C3%A0




MÔ HÌNH TCP-IP LÀ GÌ ?
* là bộ gaio thức trao đổi thông tin được sử dụng truyền tải và kết nối các thiết bị trong mạng internet
* https://www.totolink.vn/article/149-mo-hinh-tcp-ip-la-gi-chuc-nang-cua-cac-tang-trong-mo-hinh-tcp-ip.html#:~:text=vi%E1%BA%BFt%20n%C3%A0y%20nh%C3%A9.-,M%C3%B4%20h%C3%ACnh%20TCP/IP%20l%C3%A0%20g%C3%AC%3F,-TCP/%20IP%20(Transmission

* mô hình tcp/ip tiêu chuẩn có 4 lớp chồng lên nhau bắt đầu từ tầng thấp nhất là : Tầng vật lí (physical) > tầng mạng ( netword) > tầng giao vận (transport ) > tầng ứng dụng ( application )

* tầng 4 tầng ứng dụng (application)
* là lớp trên cùng của mô hình
* tầng đảm nhận vai trò giao tiếp giữ liệu 2 máy khác nhau thông qua các dịch vụ mạng khác (duyệt web, chat, gửi email, một số giao thức trao đổi dữ liệu: SMTP, SSH, FTP,...). Dữ liệu khi đến đây sẽ được định dạng theo kiểu Byte nối Byte, cùng với đó là các thông tin định tuyến giúp xác định đường đi đúng của một gói tin.

* tầng 3 tầng giao vận (transport)
* để xử lý vấn đề giao tiếp giữa các máy chủ trong một mạng hoặc khác mạng nhau thông qua bộ định tuyến tại dây dữ liế sẽ phân đoạn bằng nhaun nhưng nhỏ hơn 64 kb cấu trúc dầy đủ của một segment lúc này là header chưa thông tin điều khiển và sau đó là dữ liệu
* trong tầng này bao gồm 2 giao thức cốt lõi là tcp và udp
* TCP đảm bảo chất lượng gói tin nhưng tiêu tốn thời gian khá lâu để kiểm tra đầy đủ thông tin từ thứ tự dữ liệu cho đến việc kiểm soát vấn đề tắc nghẽn lưu lượng dữ liệu
* UDP cho thấy tốc độ nhanh hơn nhưng không đảm bảo dữ liệu gửi đi

*tầng 2 tầng mạng internet
* 1 giao thức chịu trách nhiệm truyền tải dữ liệu một cách logic trong 

* https://www.totolink.vn/article/149-mo-hinh-tcp-ip-la-gi-chuc-nang-cua-cac-tang-trong-mo-hinh-tcp-ip.html#:~:text=T%E1%BA%A7ng%202%20%2D%20T%E1%BA%A7ng%20m%E1%BA%A1ng%20(Internet)%C2%A0

* tầng 1 tầng vật lí (physical)
* chịu trách nhiệm  truyền dữ liệu giữa 2 liên kết trong cùng 1 mạng
* các gói được đóng vào khung gọi lag (frame) và được định tuyến đi dến đích được chỉ ban đầuđầu




