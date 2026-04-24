# Software Project Management (SPM)

本倉庫為**軟體專案管理（Software Project Management）**課程的作業紀錄，包含三份小組報告（PDF）及一份程式碼練習。

---

## 📂 目錄結構

```
SPM/
├── SPM_HW1/
│   └── SPM_HW1_GroupPart.pdf      # 作業一：小組報告
├── SPM_HW2/
│   └── SPM_HW2_Group Part.pdf     # 作業二：小組報告
├── SPM_HW3/
│   └── SPM_HW3_GroupPart.pdf      # 作業三：小組報告
└── bst.cpp                         # Binary Search Tree 程式碼練習
```

---

## 📄 作業說明

### HW1 — 軟體專案管理基礎
`SPM_HW1/SPM_HW1_GroupPart.pdf`

第一份小組作業，涵蓋軟體專案管理的基本概念與方法論。

### HW2 — 專案規劃與追蹤
`SPM_HW2/SPM_HW2_Group Part.pdf`

第二份小組作業，著重於專案計畫的制定、工作分解結構（WBS）以及進度追蹤。

### HW3 — 風險管理與品質保證
`SPM_HW3/SPM_HW3_GroupPart.pdf`

第三份小組作業，討論軟體專案中的風險識別、評估與品質保證策略。

---

## 💻 程式碼：Binary Search Tree（`bst.cpp`）

`bst.cpp` 為 C++ 實作的二元搜尋樹（Binary Search Tree），提供以下操作：

| 功能 | 說明 |
|------|------|
| `insert(int d)` | 插入一個整數節點 |
| `remove(int d)` | 刪除指定數值的節點（支援葉節點、單子節點、雙子節點三種情形） |
| `print_inorder()` | 中序遍歷（In-Order Traversal） |
| `print_preorder()` | 前序遍歷（Pre-Order Traversal） |
| `print_postorder()` | 後序遍歷（Post-Order Traversal） |

### 編譯與執行

```bash
g++ -o bst bst.cpp
./bst
```

執行後會出現互動式選單，可依選項進行節點的新增、刪除與各種遍歷。

---

## 🛠️ 開發環境

- **語言**：C++
- **編譯器**：GCC / MSVC（原始碼含 `#include "stdafx.h"`，可改用 MSVC 或移除後以 GCC 編譯）

