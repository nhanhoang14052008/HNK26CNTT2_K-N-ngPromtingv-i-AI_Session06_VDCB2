# KHẮC PHỤC LỖI KHAI BÁO BIẾN SỐ TRONG PROMPT MẪU

## Bước 1: Phân tích lỗi

Prompt sử dụng hai kiểu khai báo biến khác nhau: `[language]` và `{audience}`. Điều này khiến AI khó nhận diện và thay thế biến tự động, gây thiếu nhất quán khi sử dụng prompt mẫu.

## Bước 2: Đồng bộ biến số

**Prompt sau khi sửa:**

Hãy viết một bài chia sẻ về **Ứng dụng AI trong Học tập & Nghiên cứu** bằng ngôn ngữ [NGÔN_NGỮ]. Dành cho đối tượng [ĐỐI_TƯỢNG].

**Kết luận:** Sử dụng thống nhất biến số dạng `[TÊN_BIẾN]` viết hoa, không dấu cách để dễ nhận diện, thay thế và tự động hóa.
