# Kế hoạch triển khai PHUONG-01@1 — DEV
Được giao chuẩn bị file và đưa lên GitHub trong chat. Không coi yêu cầu này là phê duyệt toàn bộ Contract DEV của chuẩn 2.1.0.
Phạm vi: bộ nhớ dự án Phương, main chung, bốn vai trò và bốn inbox. Không sao chép nguyên mô hình 3 người của dự án A.
Nguồn và phân loại xem README. S1 là định hướng; S2 là hồ sơ thứ cấp; S3 là phân công hiện hành có ưu tiên so với vai minh họa cũ.

## Kế hoạch file
| F-ID | Hành động | File/nhóm | Mục đích và chủ |
|---|---|---|---|
| F01 | UPDATE | README.md | Điểm bắt đầu, Hoa |
| F02 | CREATE | MASTER.md | 7 mục tổng quan, Hoa |
| F03–F06 | CREATE | roles/ (4 file theo registry) | Tiến độ theo chức năng, từng chủ vai |
| F07–F10 | CREATE | inbox/ (4 file theo registry) | Cập nhật nguồn, từng thành viên |
| F11 | CREATE | log.md | Nhật ký tổng hợp, Hoa |
| F12 | CREATE | CONTRIBUTING.md | Cách cập nhật chung, Hoa |
| F13 | CREATE | AGENTS.md | Giới hạn thao tác AI, Hoa |
| F14 | CREATE | FILE-REGISTRY.md | Danh mục file thực, Hoa/Trung Anh hỗ trợ |
| F15 | CREATE | KE-HOACH-TRIEN-KHAI.md | Triển khai, điểm cần nghiệm thu, Hoa |

Không tạo file Design vì Cường không được phân công Design. Không tạo thêm inbox chị Phương khi chưa có yêu cầu tham gia repo. Theo yêu cầu bổ sung ngày 27/10, tài liệu văn bản được gom trong DU-LIEU-NGUON.md; video/ảnh chỉ ghi link. Không tạo số liệu giả hoặc nhiệm vụ đã nhận giả.
Quan hệ: nguồn + inbox → roles theo chức năng → MASTER tổng quan; log ghi lượt tổng hợp; registry quản lý đường dẫn.
Tên ngắn phục vụ vận hành; chưa có SKILL/A7 gốc để xác minh ngoại lệ naming. Chưa tuyên bố đạt chuẩn AI FILE CONTROL.

## Những gì chưa nghiệm thu theo chuẩn 2.1.0
- Contract CT-MASTER/ROLE/INBOX/PROJECT-LOG/AGENTS/CONTRIBUTING/REGISTRY: chỉ tham chiếu ý tưởng, chưa có xác nhận duyệt từng version.
- Kiến trúc 15 file, tên ngắn và quy trình trong bản này: chờ Hoa rà soát.
- Chưa chạy bộ T01–T29; không ghi PASS hoặc STABLE.
- Triển khai thực là bản DEV theo yêu cầu trực tiếp trong chat; không chứng nhận tuân thủ đầy đủ các Gate của tài liệu DEV.
- Đã giữ D-C01..03: tổng hợp chỉ MASTER/log; checkbox có kết quả + duyệt + tác vụ riêng; roles cập nhật riêng.

## Việc tiếp theo
Các đầu việc dưới đây là ĐỀ XUẤT cho Hoa giao, chưa có deadline hoặc xác nhận nhận việc.
| Ưu tiên | Việc | Đề xuất người phụ trách | Kết quả cần có |
|---|---|---|---|
| 1 | Xem lại MASTER và phân công; chốt người duyệt cuối | Hoa | Ghi nhận duyệt/chỉnh sửa có ngày |
| 1 | Kiểm tra private, mời thành viên, chốt cách cập nhật main | Hoa; Trung Anh hỗ trợ | Quyền truy cập được kiểm tra |
| 1 | Kiểm tra bot với video thật | Cường; Trung Anh hỗ trợ kỹ thuật | Bước thử, kết quả, giới hạn; xác nhận đã sửa hoặc phương án khác |
| 1 | Chốt checklist video và quy trình kịch bản–shot list–xác minh–quay–dựng–duyệt | Cường + Linh đề xuất; Hoa chốt | Checklist thống nhất, không tự áp tiêu chí nháp |
| 2 | Xác nhận nơi gửi plan/video và nhịp phản hồi | Cường với chị Phương | Một đầu mối và mốc phản hồi được hai bên xác nhận |
| 2 | Thu thập dữ liệu gốc từng video và kênh | Linh | Link, ngày đăng, thời điểm đo, lượt xem/giữ chân/tương tác nếu có |
| 2 | Xác định cách ghi nhận nguồn khách hàng | Cường + Linh | Phân biệt xem video, liên hệ, lead, cuộc hẹn, giao dịch; chưa có dữ liệu giữ trống |
| 3 | Tổng hợp lượt đầu từ cập nhật thật | Hoa | Chỉ MASTER/log đổi; các mục chờ không bị đóng nhầm |

## Tiêu chí rà soát nội dung
MASTER có đủ 7 mục; nguồn truy vết được; vai trò đúng S3; không tạo deadline/KPI; bot chưa bị ghi sửa xong; 15 ngày báo nộp không biến thành 15 video đạt chuẩn.
README/registry dẫn tới file tồn tại. Dữ liệu thiếu ghi rõ. Bằng chứng GitHub và quyền truy cập chỉ báo khi kiểm tra thực.

## Bổ sung PHUONG-01@2 — 27/10/2026
Yêu cầu trực tiếp trong chat: tự phân chia dữ liệu vào file phù hợp, bổ sung phần thiếu; giảm số file; video/ảnh chỉ gắn link.
Đây là tác vụ nhập và phân bổ nhiều nhóm dữ liệu được giao cụ thể, không phải lượt tổng hợp định kỳ chỉ MASTER/log.
- F16 CREATE DU-LIEU-NGUON.md: một file mới duy nhất, chứa bản đọc được hai Docs, bản toàn văn hai tài liệu địa phương, nguồn/ngày nhập, danh mục link và chỗ lưu kiến thức địa phương.
- UPDATE README, FILE-REGISTRY, CONTRIBUTING, MASTER, log, kế hoạch này và bốn roles để dẫn nguồn và phân bổ dữ liệu.
- Không sửa AGENTS hoặc inbox; không đóng checkbox; không tạo file/video/ảnh nhị phân; không tạo số liệu hoặc link giả.
- Bộ file hiện có 16 Markdown. Không chứng nhận Contract hoặc naming đã được duyệt theo chuẩn DEV 2.1.0.
- Thay yêu cầu cũ chỉ dẫn link tài liệu dài: bản văn bản nay được lưu trong F16 theo yêu cầu mới. Media chỉ giữ link.
- Lịch sử 04–25/10 vẫn là S2 tổng hợp; ngày nhập 27/10 không làm mới trạng thái hoạt động kênh.

## Danh sách dữ liệu còn thiếu — nơi bổ sung
Tất cả đều CHƯA ĐỦ DỮ LIỆU/CHỜ XÁC NHẬN, trừ phần nguồn đã nhập được ghi rõ.
Người hỗ trợ dưới đây là đề xuất để Hoa giao, không phải phân công đã nhận; chưa có deadline.
| Mã | Còn thiếu / cần xác nhận | Nơi điền chính | Đề xuất hỗ trợ | Đủ khi |
|---|---|---|---|---|
| TH-01 | Chat gốc 04–25/10 và diễn biến sau 25/10 | DU-LIEU-NGUON.md / link bản xuất | Cường | Có ngày, người nói, nội dung, xuất xứ; phân biệt với hồ sơ thứ cấp |
| TH-02 | Video/ảnh/footage/kịch bản và trạng thái từng sản phẩm | roles/phan-tich-noi-dung.md | Linh, Cường | Mỗi sản phẩm có mã, URL, ngày, phiên bản, trạng thái có nguồn; không cần tải media vào Git |
| TH-03 | Phản hồi, bản sửa và kết quả duyệt từng video | roles/khach-hang-huong-dan.md | Cường | Có link/mã video + phiên bản, lỗi/thời điểm, phản hồi, người/ngày duyệt |
| TH-04 | Link kênh, tài khoản, nền tảng, số liệu theo kỳ | roles/phan-tich-noi-dung.md | Linh | Có thời điểm đo, định nghĩa chỉ số và link số liệu; chưa có không điền 0 |
| TH-05 | Liên hệ/lead/cuộc hẹn/giao dịch và quy nguồn | roles/phan-tich-noi-dung.md | Linh, Cường | Có kỳ đo và căn cứ quy nguồn, tách từng tầng; không đưa thông tin riêng tư khách hàng |
| TH-06 | Kết quả thử bot, môi trường lỗi và cách xử lý | roles/tro-ly-ky-thuat.md | Trung Anh, Cường | Link bot đã có; còn cần ca thử video thật, kết quả, giới hạn/phương án; xác nhận người nhận xử lý |
| TH-07 | URL web, chức năng, lỗi và kết quả freelancer | roles/tro-ly-ky-thuat.md | Trung Anh | Có URL, phạm vi công việc, ca lỗi, bản sửa, kết quả kiểm tra/duyệt; thuê không đồng nghĩa sửa xong |
| TH-08 | Checklist chính thức, preset/chuẩn kỹ thuật, người duyệt | roles/khach-hang-huong-dan.md; quyết định tại MASTER | Cường, Linh đề xuất; Hoa chốt | Có bản/version được duyệt; xác định 30 fps và 5 lần liên tiếp có được áp dụng không |
| TH-09 | Nơi gửi plan/video, nhịp phản hồi, bot trước/sau dựng | roles/khach-hang-huong-dan.md | Cường | Có xác nhận quy trình với chị Phương và bằng chứng vận hành |
| TH-10 | Ưu tiên, người nhận việc, deadline, lịch tổng hợp | roles/quan-ly.md; MASTER tóm tắt | Hoa | Có quyết định ngày/người chốt; thành viên xác nhận tiến độ qua inbox |
| TH-11 | 15 câu hỏi coaching trong S1; kiến thức BMT có xác minh | roles/quan-ly.md cho quyết định; DU-LIEU-NGUON.md cho kiến thức | Hoa, Cường, Linh | Câu hỏi có trả lời/người chốt; kiến thức có trải nghiệm, thời điểm, nguồn/link |
| TH-12 | Quyền kho và tài nguyên, khả năng tra nguồn độc lập | roles/quan-ly.md / ghi nhận quản trị | Hoa, Trung Anh | Kiểm tra private/quyền cộng tác viên/quyền xem link; không suy quyền từ việc có URL |

Dữ liệu còn thiếu đã có vị trí và tiêu chí bổ sung; KHÔNG có nghĩa các giá trị đó đã được cung cấp.
Bản toàn văn S4/S5 chỉ giúp tra yêu cầu, không thay thế SKILL/A7 gốc chưa có hoặc tự hoàn tất cổng Contract.

## Câu hỏi quản lý trong S1 cần trả lời
Nguồn: tab “Câu hỏi”, giữ nguyên văn tại DU-LIEU-NGUON.md; dưới đây là chỉ mục rút gọn, tất cả CHỜ TRẢ LỜI:
1. Mục tiêu bộ tài liệu có phải giúp chị tự tư duy thay vì team đưa đáp án?
2. Có yêu cầu tự đi trọn chuỗi mục tiêu kênh → ý tưởng → video → nội dung → hình ảnh?
3. Ưu tiên năng lực tự tư duy hay chất lượng video ngắn hạn khi xung đột?
4. Khi ý tưởng chưa tốt, hỏi trước hay nói ngay vấn đề và phương án?
5. Ranh giới hỏi ngược về tư duy và giải thích trực tiếp về chuyên môn?
6. Sau nhiều vòng chưa tìm ra, tiếp tục hỏi, gợi ý hay giải thích?
7. Team được sửa trực tiếp draft/kịch bản hay chỉ phản hồi để chị tự sửa?
8. Có coaching sát 2–3 lần đầu, và giảm hỗ trợ theo tiêu chí nào?
9. Hiểu tư duy được chứng minh bằng giải thích lại, áp dụng một lần hay nhiều lần?
10. Trả lời đúng nhưng làm sai thì được coi đã hiểu chưa?
11. “Mục tiêu tháng đầu” và dạng content thứ hai được nêu trong câu hỏi đã được chốt chưa?
12. “Làm chủ hai dạng content” được định nghĩa và đo thế nào?
13. Tháng đầu cần tư duy chuỗi video hay từng video?
14. Dạy từ kinh nghiệm BĐS của chị hay cần framework dùng chung? Mốc kinh nghiệm trong câu hỏi chưa được kiểm chứng.
15. Định vị cuối giữ “hiểu BMT” hay cụ thể hơn gắn Đan Phương BĐS?

Không tự coi các tiền đề nằm trong câu hỏi (tháng đầu, hai dạng content, kinh nghiệm) là mục tiêu/KPI/sự kiện đã xác nhận.

## Kiểm tra gói dữ liệu ngày 27/10
Kiểm tra kỹ thuật: bản lưu chứa văn bản S1/S2 từ connector, S4/S5 từ file được cung cấp; 8 tab S1 có chỉ mục; link bot lấy từ hyperlink thật; một file mới; inbox và AGENTS giữ nguyên; MASTER đủ 7 mục; đường dẫn nội bộ đúng.
Giới hạn: nguồn Google Docs được lưu dạng văn bản, không giữ ảnh/bình luận/bố cục/lịch sử. S2 chưa đối chứng chat/video gốc. Chưa chạy nghiệm thu T01–T29 hoặc kiểm thử web/bot; chưa xác minh private/quyền cộng tác viên.
