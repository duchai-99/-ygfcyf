# Vấn đề
Bạn đang cần đẩy code lên GitHub để kịp deadline, nhưng Terminal báo lỗi: _error: open(".git/FETCH_HEAD"): Permission denied_. Bạn đã thử chạy lại nhưng không được.
# Yêu cầu 
-   Sử dụng Công thức Prompt 3 Thành phần để nhờ AI giải thích lỗi này một cách bình dân nhất.
    
-   Giả sử AI hướng dẫn bạn dùng quyền **Run as Administrator**, hãy thực hiện và chụp ảnh màn hình minh họa (tuân thủ các mẹo chụp ảnh chuyên nghiệp: khoanh vùng lỗi, bảo mật thông tin cá nhân).
    
-   Nếu vẫn không sửa được, hãy soạn một tin nhắn nhờ giảng viên hỗ trợ tuân thủ đúng Bug Reporting Framework.
# Cách làm 

## 1. Prompt 3 Thành phần (Gửi AI)

> _"Tôi đang bị lỗi `error: open(".git/FETCH_HEAD"): Permission denied` khi chạy Git. Hãy giải thích nguyên nhân bằng từ ngữ bình dân và chỉ cách sửa ngắn gọn."_

## 2. Thao tác & Chụp ảnh minh họa

-   **Thực hiện:** Click phải vào **Git Bash / Terminal** ➔ chọn **Run as administrator**.
    
-   **Mẹo chụp ảnh:** Khoanh đỏ dòng _Run as administrator_ và đoạn log lỗi; làm mờ tên User máy tính.
    

## 3. Tin nhắn gửi Giảng viên (Bug Report)

Plaintext

```
Thầy/Cô ơi, em gặp lỗi Git Permission Denied khi push code:
- OS: Windows 11 | Lệnh: git push origin main
- Log lỗi: error: open(".git/FETCH_HEAD"): Permission denied
- Đã thử: Chạy Terminal bằng Run as Administrator nhưng vẫn bị.
Em gửi kèm ảnh chụp màn hình, nhờ Thầy/Cô h
```
