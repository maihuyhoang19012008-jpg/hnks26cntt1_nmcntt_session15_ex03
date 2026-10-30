

# VẤN ĐỀ 
- Các thông báo kỹ thuật về cảm biến bị lẫn lộn giữa các tin nhắn tán gẫu và meme hài hước. 
- Thành viên thường xuyên quên deadline vì tin nhắn bị đè nát.
# YÊU CẦU 

- Thiết kế cấu trúc Channels / Topics cho dự án trên Lark hoặc Slack để tách biệt thảo luận kỹ thuật, thông báo và giải trí.
- Áp dụng tính năng Reply in Thread để giữ cho khung chat chính luôn sạch đẹp.
# BÀI LÀM 
- Sơ đồ kiến trúc kênh : Danh sách các Channel cần có và quy định nội dung cho từng kênh.
- Bản quy ước giao tiếp: 3 quy tắc vàng để tránh No-Hello Trap và spam @all.
## Phần 1
Thiết kế cấu trúc danh sách các Channel 

|Kênh|Mục đích|
|-|-|
|Thông báo quan trọng |**admin đăng**,mọi người chỉ được rep trong luồng tin nhắn|
|Hệ thống|Công bố bản phát hành, cập nhật tính năng mới,Mỗi bản = 1 chủ đề, phản hồi vào thread|
|Ngoài công việc| Nhóm bàn luận đời từ cuộc sống |
|Thể thao giải trí | Chia sẽ và hội thể thao | 
## Phần 2 
**Quy tắc 1:** Không "Hello" trống Gửi luôn nội dung Đúng: Gửi cả câu hỏi có  ngữ cảnh trong cùng 1 tin nhắn
**Quy tắc 2:** @ đúng người . Không spam @all là Sai: @all hỏi một việc chỉ cần 1 người trả lời. 
 Hỏi việc cụ thể  @tên_người_chịu_trách_nhiệm 
 **Quy tắc 3:** Trả lời trong Thread  Giữ khung chat sạch Sai: Trả lời trực tiếp dưới tin nhắn  làm chìm chủ đề khác. 
  Đúng: Mọi trao đổi xoay quanh 1 vấn đề  
