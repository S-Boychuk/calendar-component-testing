# 📑 Test Cases Suite

| ID | Test Case Title | Steps | Expected Result | Status | Linked Bug |
| :--- | :--- | :--- | :--- | :---: | :--- |
| **TC-001** | Verify calendar opening and layout | 1. Click "Select date" field.<br>2. Observe weekday header. | 1. Widget opens.<br>2. Weekdays: SU to SA. | 🟢 **PASS** | — |
| **TC-002** | Verify calendar navigation and restrictions | 1. Open calendar.<br>2. Navigate months.<br>3. Click future date. | 1. Current month shown.<br>2. Month changes.<br>3. Future dates blocked. | 🟢 **PASS** | — |
| **TC-003** | Verify date selection and widget toggle behavior | 1. Select date.<br>2. Reopen widget.<br>3. Click outside.<br>4. Click arrow icon. | 1. News filtered.<br>2. Widget opens.<br>3. Widget closes.<br>4. Widget closes and remains closed. | 🔴 **FAIL** | `BUG-001` |
| **TC-004** | Verify date reset on page reload | 1. Select date.<br>2. Reload page. | 1. News filtered.<br>2. Reset to "Select date". | 🟢 **PASS** | — |
| **TC-005** | Verify "No news found" placeholder | 1. Select date with no news. | 1. Placeholder shown. | 🟢 **PASS** | — |
| **TC-006** | Verify keyboard input restrictions | 1. Type text.<br>2. Type date.<br>3. Edit/Delete. | 1. Input blocked.<br>2. Input blocked.<br>3. Edit blocked. | 🔴 **FAIL** | `BUG-002`, `BUG-003` |
| **TC-007** | Verify calendar responsiveness | 1. Mobile view.<br>2. Open widget.<br>3. Interact. | 1. Layout adaptive.<br>2. Fully visible.<br>3. Easily clickable. | 🟢 **PASS** | — |
| **TC-008** | Verify combined filtering (Search + Calendar) | 1. Enter keyword, press Enter, then select date.<br>2. Select date, then enter keyword, press Enter. | 1. News feed displays only items matching BOTH the keyword and the selected date.<br>2. News feed displays only items matching BOTH the keyword and the selected date. | 🔴 **FAIL** | `BUG-004`, `BUG-005` |
