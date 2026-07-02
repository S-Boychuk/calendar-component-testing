# 🐛 Bug Reports Log

| ID | Summary | Steps to Reproduce | Actual vs Expected | Severity | Priority |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **BUG-001** | Calendar widget flashes/reopens | 1. Open widget.<br>2. Click arrow icon. | **Actual:** Widget closes and instantly reopens.<br>**Expected:** Widget should close and remain closed. | Low | Low |
| **BUG-002** | Input allows manual text entry | 1. Click input.<br>2. Type text/date and press Enter. | **Actual:** Text remains in the field and news is not filtered.<br>**Expected:** Field must be readonly. | Medium | Medium |
| **BUG-003** | Keyboard edit triggers wrong state | 1. Select date.<br>2. Backspace/Delete to edit. | **Actual:** Shows "No news found".<br>**Expected:** Input should be blocked. | Medium | Medium |
| **BUG-004** | Search results not rendered (200 OK) | 1. Enter keyword in search bar.<br>2. Press Enter. | **Actual:** UI shows empty state; pagination visible.<br>**Expected:** Render results; hide pagination. | High | High |
| **BUG-005** | Search ignores date filter | 1. Select date.<br>2. Search by keyword. | **Actual:** Search ignores date filter.<br>**Expected:** Results should be filtered by both keyword and selected date. | High | High |
