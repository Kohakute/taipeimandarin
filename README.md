[README.md](https://github.com/user-attachments/files/34346374/README.md)
# 臺北華語 A1–B1 |

Ứng dụng web tĩnh (**Single-Page Static Web App**) 



| Tính năng cốt lõi | Mô tả chi tiết | Lợi ích thực tế tại Đài Bắc |
| :--- | :--- | :--- |
| **Chia nhỏ 3–10 từ / phiên học** | Thanh trượt và nút chọn nhanh 3, 5, 7 hoặc 10 từ mỗi lần học | Tránh quá tải nét chữ Hán phồn thể, dễ học tranh thủ trên tàu MRT hoặc giờ nghỉ giữa tiết |
| **Chuẩn từ vựng Đài Loan (繁體字)** | 100% chữ Hán phồn thể và từ vựng bản địa Đài Bắc (`捷運`, `悠遊卡`, `載具`, `便當`, `內用/外帶`, `加簽`) | Không bị nhầm lẫn với từ vựng giản thể Đại Lục khi giao tiếp thực tế |
| **Cầu nối Âm Hán Việt & Chiết tự** | Giải nghĩa từng bộ thủ kèm âm Hán Việt tương ứng cho từng từ | Giúp người Việt nhớ mặt chữ và đoán nghĩa từ ghép nhanh gấp 3 lần |
| **Song ngữ Trung – Anh – Việt (EMI)** | Tích hợp thuật ngữ tiếng Anh đại học tương đương bên cạnh chữ Hán và nghĩa Việt | Hỗ trợ trực tiếp cho sinh viên theo học chương trình giảng dạy bằng cả tiếng Anh và tiếng Trung |
| **Phản xạ nghe – đáp thực tế** | Hiển thị câu người Đài thường hỏi nhanh và gợi ý câu trả lời gọn 2–4 chữ | Xử lý mượt các tình huống ở 7-Eleven, FamilyMart, chợ đêm, trạm MRT, phòng khám NHI và lớp học |
| **Phát âm chuẩn `zh-TW` (1.0x & 0.65x)** | Tích hợp Web Speech API giọng Đài Loan tốc độ thường và tốc độ chậm | Luyện nghe chuẩn khẩu âm Đài Bắc ngay từ trình độ nhập môn |
| **Lưu tiến độ tự động (`localStorage`)** | Lưu từ đã thuộc, từ cần ôn, điểm XP, Sổ tay yêu thích và từ tự thêm ngay trên trình duyệt | Không cần cài đặt cơ sở dữ liệu hay đăng nhập tài khoản phức tạp |

## Lộ Trình Học Từ Con Số 0 Đến Trình Độ B1 (TOCFL)

| Giai đoạn | Cấp độ | Trọng tâm kiến thức & Chủ đề thực tế | Ví dụ từ vựng & Mẫu câu trọng tâm |
| :--- | :--- | :--- | :--- |
| **Bước 0** | **Nhập môn Phát âm** | 4 thanh điệu + thanh nhẹ, 3 quy tắc biến điệu (`你好`, `不要`, `一個`), phân biệt âm bật hơi và khẩu âm Đài Bắc | `不好意思 (bù hǎoyìsi)`, `請問 (qǐngwèn)`, `謝謝 / 不會` |
| **Bước 1** | **TOCFL A1 (Sơ cấp 1)** | Chào hỏi, mua đồ 7-Eleven/FamilyMart, gọi trà sữa & cơm hộp, đi tàu MRT và xe buýt Đài Bắc | `內用 / 外帶`, `載具`, `微波`, `半糖少冰`, `悠遊卡`, `捷運出口` |
| **Bước 2** | **TOCFL A2 (Sơ cấp 2)** | Đời sống sinh viên, đăng ký môn học đại học song ngữ, khám bệnh bằng thẻ NHI, thuê nhà trọ, nhận hàng Shopee | `選課 / 加簽`, `學分`, `分組報告`, `健保卡 / 掛號`, `房東 / 水電費`, `專用垃圾袋` |
| **Bước 3** | **TOCFL B1 (Trung cấp 1)** | Thảo luận học thuật, viết báo cáo nghiên cứu, xin giấy phép làm thêm, gia hạn thẻ ARC, mở tài khoản bưu điện, xin thực tập | `居留證`, `工作證 / 打工`, `時薪 / 排班`, `研究方法 / 文獻探討`, `人工智慧 / 資訊工程`, `履歷表` |

## Quy Trình Học 3 Bước Trong Mỗi Phiên (3–10 Từ)

1. **Bước 1 — Học Thẻ Từ & Mẫu Câu Thực Tế (Flashcard)**:
   - Quan sát chữ Hán phồn thể cỡ lớn, Pinyin (có thể bật/tắt để tự kiểm tra trí nhớ), Âm Hán Việt và thuật ngữ tiếng Anh giảng đường.
   - Bấm **🔊 Nghe chuẩn Đài (1.0x)** hoặc **🐢 Nghe chậm (0.65x)** để luyện phát âm từng từ và cả câu ví dụ.
   - Đọc mục **👂 Phản xạ khi người Đài hỏi nhanh** để nắm trước câu hỏi của nhân viên/giáo sư và câu trả lời ngắn gọn.
   - Đánh dấu **✅ Đã thuộc (+15 XP)**, **🔄 Cần ôn lại**, hoặc **⭐ Lưu sổ tay**.
2. **Bước 2 — Trắc Nghiệm Phản Xạ & Tình Huống (Quiz)**:
   - Hệ thống tự động tạo bộ câu hỏi trắc nghiệm từ chính 3–10 từ bạn vừa học trong phiên.
   - Kết hợp câu hỏi nhận diện mặt chữ Hán phồn thể và câu hỏi xử lý tình huống giao tiếp tại Đài Bắc.
3. **Bước 3 — Ghép Thẻ Nhanh (Speed Match)**:
   - Trò chơi ghép cặp nhanh giữa ô **Chữ Hán phồn thể** và ô **Nghĩa tiếng Việt + Pinyin + Âm Hán Việt** để khắc sâu trí nhớ ngắn hạn sang dài hạn.

## Cấu Trúc Thư Mục Dự Án

| Tên file | Vai trò trong dự án |
| :--- | :--- |
| `index.html` | Toàn bộ mã nguồn giao diện, kho từ vựng A1–B1, bộ phát âm `zh-TW` và logic học tập (Single-File App) |
| `README.md` | Tài liệu giới thiệu dự án, hướng dẫn học tập và hướng dẫn triển khai lên GitHub Pages |
| `.nojekyll` | File cấu hình giúp GitHub Pages phục vụ trực tiếp trang tĩnh nhanh chóng mà không cần qua bước biên dịch Jekyll |

## Hướng Dẫn Đưa Ứng Dụng Lên GitHub Pages Miễn Phí

### Cách 1: Tải file trực tiếp trên giao diện web GitHub (Nhanh nhất - 1 phút)

1. Đăng nhập vào tài khoản GitHub của bạn và bấm nút **New repository**.
2. Đặt tên repository (ví dụ: `taipei-mandarin`), chọn chế độ **Public**, rồi bấm **Create repository**.
3. Chọn **uploading an existing file**, kéo thả 3 file `index.html`, `README.md` và `.nojekyll` (từ gói `.zip` hoặc tải trực tiếp trong ứng dụng) vào rồi bấm **Commit changes**.
4. Vào mục **Settings → Pages** của repository, tại phần **Build and deployment → Branch**, chọn nhánh `main` và thư mục `/ (root)`, sau đó bấm **Save**.
5. Đợi khoảng 30–60 giây, ứng dụng của bạn sẽ hoạt động tại địa chỉ:
   `https://<ten-github-cua-ban>.github.io/taipei-mandarin/`

### Cách 2: Đẩy mã nguồn bằng Git trên Terminal / Command Prompt

```bash
mkdir taipei-mandarin && cd taipei-mandarin
# Copy file index.html và README.md vào thư mục này
git init
git branch -M main
git add index.html README.md
git commit -m "Initial commit: Taipei Mandarin A1-B1 web app"
git remote add origin https://github.com/TEN_USER_CUA_BAN/taipei-mandarin.git
git push -u origin main
```

## Mẹo Sử Dụng Hiệu Quả Trên Điện Thoại Tại Đài Bắc

- **Ghim ra màn hình chính (Add to Home Screen)**: Mở đường link GitHub Pages của bạn bằng trình duyệt Safari (iOS) hoặc Chrome (Android), chọn **Thêm vào màn hình chính (Add to Home Screen)** để dùng như một ứng dụng di động thực thụ.
- **Tự thêm từ vựng chuyên ngành**: Khi gặp từ mới trên slide bài giảng của giáo sư hoặc biển hiệu ngoài đường ở Đài Bắc, hãy mở tab **📚 Kho từ A1–B1 & Sổ tay** → bấm **➕ Thêm từ vựng mới** để lưu riêng vào bộ nhớ trình duyệt của bạn.
