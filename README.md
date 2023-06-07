# Youtube_Analysis

## Mục tiêu

Được thành lập vào năm 2005, Youtube đã phát triển trở thành công cụ tìm kiếm lớn thứ hai trên thế giới (sau Google), xử lý hơn 3 tỷ lượt tìm kiếm mỗi tháng. Tuy nhiên, làm thế nào để có được một video thành công và nhiều lượt xem vẫn là một câu hỏi khó với những nhà sáng tạo nội dung. Liệu thời gian upload video có ảnh hưởng đến lượt xem, hay những hashtag nào giúp cho video nổi bật hơn?
Với sở thích âm nhạc và những kiến thức phân tích dữ liệu học được, để làm sáng tỏ những câu hỏi trên, dự án nhỏ này sẽ bắt đầu khám phá số liệu của một số kênh nổi bật trong ngành công nghiệp âm nhạc.

Với dự án này, em mong muốn tìm hiểu thêm: 
- Youtube API và cách lấy dữ liệu từ Youtube
- Phân tích dữ liệu và trả lời một số câu hỏi như:
    
    
## Các bước phân tích
    1. Tạo developer key, chuẩn bị các thư viện
    2. Chuẩn bị dữ liệu
    3. Khám phá dữ liệu
    4. Kết luận


## Kết luận

Trong dự án này, em đã khám phá được những thông tin thú vị từ 9 channel nổi tiếng trong ngành công nghiệp âm nhạc:
- Video càng có nhiều lượt thích và bình luận thì video đó càng nhận được nhiều lượt xem (không đảm bảo rằng đây là mối quan hệ nhân quả, nó chỉ đơn giản là một mối tương quan và có thể tác động theo cả hai chiều). Lượt thích dường như là một chỉ số tương tác tốt hơn bình luận và số lượt thích dường như tuân theo "bằng chứng xã hội", có nghĩa là video càng có nhiều lượt xem thì càng có nhiều người thích video đó.
- Video thường được upload vào thứ 5 và 13h. Đây cũng là ngày giờ có nhiều lượt view nhất.
- Sơn tùng MTP là kênh có ảnh hưởng nhất khi lượt view, comment và subcribe đều vượt trội. 
- Số lượng tag của mỗi video trong khoảng từ 5 đến 40. 

Những hạn chế của dự án:
- Số lượng video phân tích khá nhỏ
- Vẫn còn nhiều khía cạnh có thể khai thác từ dữ liệu

Hướng phát triển trong tương lai:
- Tăng số lượng channel và video để có cái nhìn tổng quát hơn
- Phân tích trạng thái của comment( tích cực, tiêu cực hay trung tính)
- Dự đoán số lượt view video tiếp theo của kênh

