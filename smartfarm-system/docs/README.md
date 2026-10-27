# Hệ thống giám sát Trạm cảm biến Nông Trại.

## Hướng dẫn chạy scripts:

```shell
.\scripts\auto.report.ps1
```

## Check list

- [x] hoàn thiện docs
- [ ] hoàn thành excel
- [ ] soát thiết bị

## Table

| Tên                    | Đơn giá   | Loại Storage |
| ---------------------- | --------- | ------------ |
| Raspberry Pi 4 Model B | 1,450,000 | SSD          |
| Intel NUC i3           | 6,200,000 | SSD          |

## Phân tích hệ thống

- Data :2026-10-12 08:15:01 [ERROR] sensor-03 Connection TIMEOUT after 30s
- Information : Quyết định thay modem trạm sensor-03 trước thứ Sáu.
- Knowledge : Trạm sensor-03 hay mất kết nối vào buổi chiều do sóng yếu, nên cần lắp thêm anten.
- Wisdom : Hôm nay hệ thống ghi nhận 8 sự cố, trong đó 4 sự cố đến từ trạm sensor-03
