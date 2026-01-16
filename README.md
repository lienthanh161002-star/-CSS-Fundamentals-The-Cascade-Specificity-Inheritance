🛠 Lỗi thực tế: "Cú sốc" về dấu cách trong Class
Hôm nay mình đã phát hiện ra một sự thật về HTML mà mình từng hiểu lầm hoàn toàn:

Suy nghĩ cũ: Mình cứ tưởng sau dấu = trong class="..." thì tất cả chữ trong đó là tên của 1 class duy nhất.

Sự thật là: Dấu cách (space) chính là ranh giới.

Ví dụ: <div class="box inner-box"> thực chất là thẻ này đang mặc 2 chiếc áo (class box và class inner-box).

Hậu quả: Vì không biết thẻ có 2 lớp, mình đã gõ CSS sai cú pháp, dẫn đến việc trình duyệt "bó tay" không lên màu được cho box.

💡 Bài học rút ra:
Đừng nhìn bề ngoài, hãy nhìn vào dấu cách! Việc chia nhiều class giúp mình quản lý code linh hoạt hơn (Module hóa), nhưng phải cực kỳ cẩn thận khi viết CSS để gọi đúng "tên" của chúng.

🚀 Tại sao sửa như vậy lại "Nhóm 3" hơn?
Sự thấu hiểu bản chất: Bạn không chỉ sửa lỗi code, bạn đang giải thích sự thay đổi trong tư duy của mình. Nhà tuyển dụng rất thích điều này.

Dễ hiểu cho người sau: Một bạn sinh viên khác đọc vào sẽ "A ha!" vì họ cũng từng tưởng dấu cách là một phần của tên class như bạn.

Tính chính xác: Bạn đã kết nối được kiến thức HTML (cú pháp thẻ) với CSS (cách chọn selector).

Bạn đã nắm vững quy tắc "Dấu cách" này chưa? Nếu rồi, hãy dán bản chỉnh sửa này vào README và đi nghỉ ngơi thôi. Bạn đã có một ngày "ép xung" cực kỳ năng suất rồi đấy!
