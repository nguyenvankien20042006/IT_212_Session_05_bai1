# Bài 1: Phân tích & Lựa chọn Prompt tối ưu (Refactor Clean Code)

## 1. Đáp án lựa chọn

**Chọn: B**

---

## 2. Phân tích phương án B theo 5 thành phần Prompt

### 1. Vai trò (Role)
- Gán rõ vai trò: **Senior Java Developer**
- Giúp AI:
    - Tư duy theo chuẩn production
    - Áp dụng best practices (Clean Code, refactoring)

---

### 2. Mục tiêu (Objective)
- Refactor code có nested if-else
- Chuyển sang **guard clauses (return sớm)**

➡️ Mục tiêu cụ thể, rõ ràng, tránh mơ hồ.

---

### 3. Ngữ cảnh (Context)
- Class: `DiscountService`
- Logic: tính chiết khấu theo `type`, `amount`, `isHoliday`
- Yêu cầu: giữ nguyên nghiệp vụ

➡️ Giúp AI hiểu đây là **business logic quan trọng**

---

### 4. Ràng buộc (Constraints)
- Không thay đổi logic nghiệp vụ
- Không thay đổi input/output
- Dùng Java 11
- Áp dụng guard clauses

➡️ Giảm rủi ro AI sửa sai logic

---

### 5. Định dạng đầu ra (Format)
- Trả về full Java code
- Có giải thích ngắn bằng tiếng Việt

---

## 3. Vì sao phương án B tối ưu?

- Đầy đủ 5 thành phần prompt chuẩn
- Định hướng rõ kỹ thuật refactor
- Kiểm soát logic nghiệp vụ
- Output rõ ràng, dễ sử dụng

➡️ Đây là prompt chuẩn production-grade

---

## 4. Phân tích các phương án còn lại

### ❌ Phương án A
> "Tái cấu trúc code Java trên để nó đẹp hơn."

Nhược điểm:
- Không có vai trò
- Không có mục tiêu cụ thể
- Không có ràng buộc
- Không có format output

➡️ Quá mơ hồ, dễ sai kết quả

---

### ❌ Phương án C
> "Dùng Java Stream API để viết ngắn gọn nhất"

Nhược điểm:
- Sai hướng kỹ thuật
- Không phù hợp logic điều kiện nghiệp vụ
- Không đảm bảo giữ nguyên logic

➡️ Dễ gây over-engineering và lỗi logic

---

## 5. Kết luận

- **Chọn: B**
- Lý do: rõ vai trò + mục tiêu + ngữ cảnh + ràng buộc + định dạng