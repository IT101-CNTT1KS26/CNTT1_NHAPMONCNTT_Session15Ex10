# PHÂN TÍCH VÀ LỰA CHỌN CÔNG CỤ GIAO TIẾP CHO NHÓM STARTUP SINH VIÊN CAMPUSPAY



## PHẦN 1: PHÂN TÍCH & ĐỀ XUẤT (ĐA GIẢI PHÁP)

### 1. Phân tích yêu cầu bài toán (Input / Output)

* **Đầu vào (Inputs):**
* Nhóm startup sinh viên CampusPay gồm 4-5 thành viên chia thành các ban: Kỹ thuật, Thiết kế, Kinh doanh và Nhà đầu tư (bên ngoài).
* Vấn đề gặp phải: Sự cố rò rỉ dữ liệu, mất file và tin nhắn quan trọng bị trôi trong các đoạn chat thông thường, gây chậm trễ tiến độ.
* Hai luồng quan điểm: Tiếp tục dùng Zalo (quen thuộc, không mất công học) hay chuyển sang Lark Suite (chuyên nghiệp, tích hợp đầy đủ công cụ làm việc).


* **Đầu ra mong đợi (Outputs):**
* Đánh giá chi tiết ưu/nhược điểm của Zalo và Lark Suite theo 5 tiêu chí nghiệp vụ.
* Lập bảng so sánh trực quan và đưa ra quyết định lựa chọn công cụ tối ưu nhất (hoặc giải pháp lai).
* Thiết kế cấu trúc Channel trên Lark Suite và đề xuất quy tắc chống spam hiệu quả.



### 2. Phân tích ưu điểm và nhược điểm của Giải pháp A (Zalo) và Giải pháp B (Lark)

#### Giải pháp A — Zalo (Chat cá nhân truyền thống)

* **Ưu điểm:**
* Quen thuộc với tất cả thành viên, không mất thời gian cài đặt hay tìm hiểu cách sử dụng.
* Sẵn có trên mọi điện thoại cá nhân, tốc độ truyền tin nhanh, hỗ trợ gửi hình ảnh, file và ghim tin nhắn cơ bản.
* Phù hợp để liên lạc nhanh với các đối tác ngoài trường chỉ dùng Zalo.


* **Nhược điểm:**
* Dễ bị trôi tin nhắn quan trọng do dòng chat cá nhân/nhóm bị lấn át bởi các thông tin ngoài lề hoặc chat phiếm.
* Không tích hợp tính năng giao Task, đặt Deadline trực tiếp gắn liền với đoạn hội thoại.
* Tìm kiếm lại quyết định kiến trúc, file tài liệu cũ từ 2-3 tháng trước cực kỳ khó khăn.
* Thiếu không gian làm việc bất đồng bộ chuyên nghiệp (thiếu Thread chat riêng cho từng chủ đề, thiếu bộ đôi Docs/Calendar tích hợp sâu).



#### Giải pháp B — Lark Suite (Nền tảng làm việc doanh nghiệp toàn diện)

* **Ưu điểm:**
* Phân tách rõ ràng các Channel chuyên đề (`#thong-bao`, `#dev`, `#design`, `#kinh-doanh`), giúp khoanh vùng thông tin chính xác.
* Tính năng *Reply in Thread* giúp giữ khung chat chính sạch sẽ, không bị rối mắt khi bàn luận sâu vào một vấn đề.
* Chuyển đổi tin nhắn chat thành Task có Deadline bằng 1-click, gắn kết trực tiếp công việc với thảo luận.
* Khả năng tìm kiếm thông minh theo từ khóa, người gửi, loại file trong lịch sử lâu dài.
* Tích hợp đồng bộ Calendar, Docs, Video call trong cùng một nền tảng, giải quyết triệt để vấn đề phân mảnh file và mất tài liệu.


* **Nhược điểm:**
* Yêu cầu thời gian học tập ban đầu (learning curve) từ 1-2 ngày cho các thành viên chưa từng sử dụng công cụ doanh nghiệp.
* Một số đối tác bên ngoài không dùng Lark, đòi hỏi phải có cầu nối giao tiếp khác.



---

## PHẦN 2: SO SÁNH & LỰA CHỌN

### 3. Bảng so sánh 5 tiêu chí nghiệp vụ

| Tiêu chí nghiệp vụ | Giải pháp A (Zalo) | Giải pháp B (Lark Suite) |
| --- | --- | --- |
| **Tiêu chí 1 — Ngăn chặn tin nhắn bị trôi** | ❌ | ✅ |
| **Tiêu chí 2 — Quản lý công việc (Task & Deadline)** | ❌ | ✅ |
| **Tiêu chí 3 — Độ miễn phí & dễ cài đặt** | ✅ | ⚠️ |
| **Tiêu chí 4 — Tìm kiếm lịch sử (Kiến trúc, quyết định cũ)** | ❌ | ✅ |
| **Tiêu chí 5 — Giao tiếp bất đồng bộ (Đủ ngữ cảnh)** | ⚠️ | ✅ |

*Ký hiệu: ✅ Tốt | ⚠️ Trung bình | ❌ Kém*

### 4. Chốt lựa chọn & Xử lý bẫy dữ liệu

#### Đề xuất Giải pháp Lai (Hybrid Solution) tối ưu cho CampusPay:

Dựa trên phân tích và các bẫy dữ liệu đặt ra, nhóm CampusPay nên áp dụng **Giải pháp Lai**:

* **Lark Suite** làm **nền tảng cốt lõi** để quản lý toàn bộ nội bộ dự án, tài liệu kỹ thuật, task công việc và thảo luận chuyên sâu giữa 4 ban.
* **Zalo** được giữ lại đóng vai trò là **kênh ngoại giao phụ (External Gateway)** chuyên dùng để giao tiếp với các đối tác ngoài trường (những người không dùng Lark).

#### Lập luận dựa trên 3 bẫy dữ liệu:

* **Xử lý Bẫy 1 (Thành viên ban Kinh doanh chỉ dùng điện thoại):** Lark Suite cung cấp ứng dụng Mobile cực kỳ tối ưu, mượt và đầy đủ tính năng (Chat, Task, Docs, Calendar) trên cả iOS và Android. Thành viên ban Kinh doanh hoàn toàn có thể làm việc trơn tru trên điện thoại mà không bắt buộc phải có laptop.
* **Xử lý Bẫy 2 (Chi phí học tập 1-2 ngày khi deadline cận kề):** Thời gian đầu tư 1-2 ngày làm quen với Lark Suite là **hoàn toàn xứng đáng và bắt buộc**. Nếu tiếp tục dùng Zalo trong giai đoạn nước rút, nhóm sẽ mất nhiều thời gian hơn nữa để tìm lại file bị thất lạc, tranh cãi vì trôi tin nhắn và chồng chéo công việc. Đầu tư công cụ chuẩn từ đầu giúp tăng tốc độ làm việc dài hạn.
* **Xử lý Bẫy 3 (Đối tác ngoài trường chỉ dùng Zalo):** Giải pháp lai giải quyết trọn vẹn điểm này: nhóm dùng Lark cho nội bộ để đảm bảo an toàn dữ liệu và quản lý task, còn khi làm việc với đối tác bên ngoài thì sử dụng tài khoản Zalo cá nhân/nhóm riêng biệt, tránh việc đưa dữ liệu nhạy cảm của dự án lên Zalo.

---

## PHẦN 3: THIẾT KẾ & TRIỂN KHAI (NẾU CHỌN LARK)

### 5. Cấu trúc Channel cho nhóm CampusPay & Quy tắc chống Spam

Nếu triển khai Lark Suite cho nhóm 4 ban, cấu trúc Channel đề xuất tối thiểu gồm 5 kênh chuyên biệt:

1. **`#01-thong-bao-chung`**
* *Mục đích:* Kênh phát sóng các thông báo quan trọng, quyết định của trưởng nhóm, lịch họp chung.
* *Quyền đăng bài:* Chỉ Trưởng nhóm / Quản trị viên (để tránh nhiễu thông tin).


2. **`#02-dev-ky-thuat`**
* *Mục đích:* Trao đổi mã nguồn, API, kiến trúc hệ thống, báo cáo lỗi và tiến độ kỹ thuật của Ban Kỹ thuật.
* *Quyền đăng bài:* Thành viên Ban Kỹ thuật và Ban Quản lý.


3. **`#03-design-giao-dien`**
* *Mục đích:* Thảo luận UI/UX, duyệt asset đồ họa, chia sẻ link file thiết kế nguyên bản.
* *Quyền đăng bài:* Thành viên Ban Thiết kế và Ban Quản lý.


4. **`#04-kinh-doanh-marketing`**
* *Mục đích:* Thảo luận chiến lược Business Plan, kế hoạch tiếp cận khách hàng, tài liệu tài chính.
* *Quyền đăng bài:* Thành viên Ban Kinh doanh và Ban Quản lý.


5. **`#05-giao-ban-chung`**
* *Mục đích:* Thảo luận chung, chéo giữa các ban, chia sẻ thông tin cập nhật hằng ngày.
* *Quyền đăng bài:* Toàn bộ thành viên trong nhóm.



#### Cách phòng tránh tình trạng spam `@all` (Thi hành "Quy tắc cờ đỏ"):

* **Giới hạn quyền tag `@all` / `@channel`:** Chỉ cấp quyền thông báo toàn nhóm cho Trưởng nhóm hoặc khi có sự cố khẩn cấp liên quan đến toàn bộ dự án.
* **Quy tắc cờ đỏ (Red Flag Rule):** Bất kỳ thành viên nào lạm dụng tính năng tag `@all` cho các việc cá nhân, thông tin không khẩn cấp hoặc nhắc lại việc chưa đến hạn sẽ bị nhắc nhở trong các buổi họp kiểm điểm sprint tuần.
* **Khuyến khích giao tiếp bất đồng bộ (Async Communication):** Thay vì gọi hồn hay tag tên liên tục, thành viên viết rõ ràng nội dung, gắn Deadline cụ thể vào Task trên Lark để người nhận chủ động xử lý vào thời gian phù hợp mà không bị áp lực thời gian thực.