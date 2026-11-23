# CMSIS Device STM32G0 — STMicroelectronics

| Mục | Giá trị |
|---|---|
| Nguồn | https://github.com/STMicroelectronics/cmsis-device-g0 |
| Phiên bản | **v1.4.5** (`__STM32G0_CMSIS_VERSION_MAIN/SUB1/SUB2` trong `Include/stm32g0xx.h`) |
| Cách tải | Zip của nhánh `master` (không phải release tag) — commit chưa ghi lại |
| Ngày tải | 2026-11-20 |
| Phần đã chép | `Include/` → `Include/` (giữ nguyên toàn bộ thư mục) |
| Sửa đổi | Không |
| License | Apache-2.0 — xem `LICENSE.md` (chép từ gốc repo) |

File dùng trực tiếp: `stm32g0xx.h` (chọn chip qua macro `STM32G071xx`) → `stm32g071xx.h`, `system_stm32g0xx.h`.
Không dùng: `Source/Templates/` (startup `.s`, `system_stm32g0xx.c`) — dự án tự viết startup (xem CLAUDE.md).
