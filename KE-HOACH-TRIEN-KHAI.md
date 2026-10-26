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

Không tạo file Design vì Cường không được phân công Design. Không tạo thêm inbox chị Phương khi chưa có yêu cầu tham gia repo. Không sao chép tài liệu dài/video gốc; giữ link nguồn. Không tạo số liệu giả hoặc nhiệm vụ đã nhận giả.
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
