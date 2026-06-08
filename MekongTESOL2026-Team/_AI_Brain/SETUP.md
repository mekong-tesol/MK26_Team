# Mekong TESOL 2026 — AI Setup Guide

> **Dành cho thành viên mới.** Bạn không cần biết lập trình. Chỉ cần mở Claude Code (Antigravity), paste 1 câu lệnh bên dưới, và AI sẽ tự cài đặt mọi thứ.

---

## Bước 1 — Tải thư mục project về máy

Tải thư mục `_AI_Brain` từ Google Drive của team về máy tính. Ghi nhớ đường dẫn đầy đủ, ví dụ:

- **Mac**: `/Users/[tên-bạn]/Documents/MekongTESOL2026/_AI_Brain`
- **Windows**: `C:\Users\[tên-bạn]\Documents\MekongTESOL2026\_AI_Brain`

---

## Bước 2 — Mở Claude Code và paste lệnh sau

Mở Claude Code (hoặc Antigravity IDE), tạo cuộc trò chuyện mới, và paste đúng câu này:

```
Hãy đọc file _AI_Brain/SETUP.md trong thư mục project Mekong TESOL và cài đặt skills
```

> **Lưu ý:** Bạn cần mở Claude Code trong đúng thư mục chứa `_AI_Brain`. Nếu không, paste đường dẫn đầy đủ:
> `Hãy đọc file /Users/[tên-bạn]/Documents/MekongTESOL2026/_AI_Brain/SETUP.md và cài đặt skills`

---

## Bước 3 — Khởi động lại Claude Code

Sau khi AI báo cài xong → đóng và mở lại Claude Code → gõ `/` để thấy các lệnh mới.

---

---

## ═══ AGENT INSTRUCTIONS (AI đọc phần này) ═══

> Người dùng vừa yêu cầu cài đặt skills Mekong TESOL 2026. Hãy thực hiện đúng các bước sau.

### Bước A — Xác định đường dẫn

1. Xác định hệ điều hành (`uname -s` hoặc kiểm tra môi trường)
2. Xác định thư mục gốc của project (thư mục chứa `_AI_Brain`)
3. Xác định thư mục cài skills của Claude Code:
   - **macOS/Linux**: `~/.claude/`
   - **Windows**: `C:\Users\[username]\.claude\`

### Bước B — Đọc và nạp Knowledge Base

Đọc file sau và ghi nhớ toàn bộ nội dung làm context cho mọi tác vụ Mekong TESOL:

```
[project-root]/_AI_Brain/knowledge_base.md
```

Sau đó đọc thêm nếu có:
```
[project-root]/_AI_Brain/CLAUDE_PROMPT.md
[project-root]/_AI_Brain/QUICK_REF_DesignSystem.md
[project-root]/_AI_Brain/context.md
```

### Bước C — Cài đặt Skills vào Claude Code

Với **mỗi skill** trong danh sách bên dưới, thực hiện:

1. Đọc file `[project-root]/_AI_Brain/skills/[skill-name]/SKILL.md`
2. Chỉnh đường dẫn workspace trong file cho khớp với máy hiện tại (thay `/Users/macbookpro/...` bằng đường dẫn thực tế)
3. Copy file vào `~/.claude/skills/[skill-name]/SKILL.md` (tạo thư mục nếu chưa có)

**Danh sách skills:**

| Skill | Mô tả |
|-------|-------|
| `email-marketing` | Tạo email HTML theo chuẩn Design System Mekong TESOL |

> Nếu trong `_AI_Brain/skills/` có thêm thư mục khác ngoài danh sách trên → cài luôn tất cả.

### Bước D — Báo cáo kết quả

Sau khi hoàn tất, báo cáo cho người dùng:

1. ✅ Các file đã được tạo ở đâu
2. 📋 Knowledge base đã nạp — tóm tắt ngắn thông tin chính (tên hội thảo, ngày, địa điểm)
3. 🔧 Danh sách lệnh `/` mới có thể dùng và mục đích từng lệnh
4. 🔄 Nhắc khởi động lại Claude Code để thấy slash commands

---

## Danh sách Skills hiện có

| Slash Command | Mô tả |
|---|---|
| `/mekong-email-marketing` | Tạo và chỉnh sửa email HTML theo chuẩn Design System của Mekong TESOL 2026 |

---

## Người quản lý

**Trưởng nhóm:** Minh Minh — `mminhthu.0304@gmail.com`

Mọi cập nhật skills hoặc knowledge base → liên hệ Minh Minh để đồng bộ.
