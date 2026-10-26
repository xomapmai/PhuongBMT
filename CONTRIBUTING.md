# Quy tắc cập nhật của nhóm
Bản DEV đề xuất vận hành; Hoa rà soát trước khi coi là quy trình chính thức.

## Ai sửa file nào?
| Thành viên | Inbox | File vai trò |
|---|---|---|
| Hoa | inbox/hoa.md | roles/quan-ly.md |
| Trung Anh | inbox/trung-anh.md | roles/tro-ly-ky-thuat.md |
| Cường | inbox/cuong.md | roles/khach-hang-huong-dan.md |
| Linh | inbox/linh.md | roles/phan-tich-noi-dung.md |

Hoa quản lý MASTER.md và log.md. Người khác cần ủy quyền cụ thể khi sửa file ngoài phạm vi.
Khởi tạo bởi AI từ nguồn không được xem là thành viên đã báo cáo hoặc nhận việc.

## Cách ghi
Mỗi mục inbox bắt đầu bằng:
`- [ ] YYYY-MM-DD - Việc/kết quả; bằng chứng hoặc link; đang chờ ai; bước tiếp theo; deadline nếu đã được xác nhận.`
Gắn nhãn ĐỀ XUẤT nếu chưa được giao/chốt; ghi CHƯA CÓ DỮ LIỆU thay vì số 0.
Không xóa lịch sử. Chỉ chuyển [ ] thành [x] khi đã có kết quả/đã giải quyết, Hoa duyệt và chủ inbox hoặc người được ủy quyền thực hiện bằng nhiệm vụ riêng.
Đã đưa vào MASTER không đồng nghĩa đã giải quyết.
Vai trò cập nhật khi thay đổi đáng kể, đủ Phụ trách / Tiến độ / Việc tiếp theo / Vướng mắc.

## Luồng cập nhật main
1. Trước khi sửa, kiểm tra git status; nếu sạch, lấy bản mới bằng git pull --ff-only. Có thay đổi dở dang thì giữ nguyên và xử lý trước.
2. Chỉ sửa đúng file của mình, ghi nguồn và ngày sự kiện.
3. Kiểm tra git diff; commit đúng các file đã xem; push lên main nếu có quyền và được giao.
4. Push bị từ chối thì lấy thay đổi mới và xử lý xung đột; không force push. Chưa biết xử lý thì nhờ Trung Anh.
Có thể sửa file trực tiếp trên GitHub nếu có quyền; tải lại trang trước khi sửa.

## Hoa tổng hợp
Nhịp đề xuất: hàng tuần; ngày/giờ chưa chốt.
Chỉ sửa MASTER.md và log.md trong một lượt tổng hợp; đọc inbox/roles, phân loại sự kiện/đề xuất/chờ xác nhận.
Mâu thuẫn nghiệp vụ phải đưa Hoa chốt. Xuất danh sách checkbox đủ điều kiện riêng, không tự đổi inbox trong lượt tổng hợp.
Xem diff trước khi ghi phiên bản; quyền Git theo lệnh hiện hành.

## Truy cập
Dùng kho private theo yêu cầu nguồn A; cần kiểm tra trạng thái thật trên GitHub trước khi thêm dữ liệu riêng tư.
Chưa thiết lập bảo vệ nhánh, CODEOWNERS hoặc quyền cộng tác viên. Quy ước file không ngăn người có quyền write sửa file khác.
Không chia sẻ dữ liệu riêng tư hoặc thông tin xác thực qua repo.
