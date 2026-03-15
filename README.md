

## 📄 **README.md (英文版)**

```markdown
# 🎓 Student Work Management System
```
[![YouTube Demo](https://img.shields.io/badge/Demo-Watch%20on%20YouTube-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=Wtyr2uiE3wU)

This is a web-based **Student Work Management System** built with PHP and phpMyAdmin (MySQL). It allows for the management and display of outstanding student projects with different access levels for various user roles.

## ✨ Key Features

*   **Three User Roles**: The system supports **Guest**, **Student**, and **Teacher** roles, each with specific permissions.
    *   **Guest**: Can view public projects and information.
    *   **Student**: Can submit their work and manage their own profile.
    *   **Teacher**: Has administrative privileges to review, approve, manage all submissions, and oversee users.
*   **Project Showcase**: A platform to feature and organize excellent student work.
*   **Secure Access**: Includes a login and registration system to manage user access.
*   **File Management**: Supports uploading and managing project-related files.
*   **Real-time Communication**: (Implied from the project's broader context) May include features for messaging or notifications.

## 🛠️ Built With

*   **Frontend**: HTML, CSS, JavaScript
*   **Backend**: PHP
*   **Database**: MySQL (managed via phpMyAdmin)
*   **Other**: AJAX, jQuery
*   **Server Environment**: Designed for **DerServer 17** (or any PHP-compatible local server)

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   **DerServer 17** (or any local server environment that supports PHP and MySQL, such as XAMPP, WAMP, MAMP, or Laragon).
*   **phpMyAdmin** (usually included with DerServer for database management).
*   A code editor like **VS Code**, **Sublime Text**, or **PHPStorm**.
*   A web browser.
*   **Git** (optional, for cloning).

### Installation

1.  **Clone the repository** (or download the ZIP file and extract it).
    ```bash
    git clone https://github.com/LeoTheAuJai/Student_Work_Mangement_System.git
    ```

2.  **Move the project folder** to your DerServer's root directory.
    *   For **DerServer 17**, this is usually `C:\DerServer\htdocs\` or `C:\Program Files\DerServer\www\`. (Please check your specific installation path.)

3.  **Start DerServer**: Ensure both Apache and MySQL services are running in the DerServer control panel.

4.  **Set up the Database via phpMyAdmin**:
    *   Open your browser and go to **phpMyAdmin** (usually at `http://localhost/phpmyadmin` or `http://localhost/derphpmyadmin`).
    *   Create a new database (e.g., `student_work_db`).
    *   Select the newly created database.
    *   Click on the **"Import"** tab.
    *   Click **"Choose File"** and select the provided SQL file (`sms finalized version.sql`) from the project root.
    *   Click **"Go"** or **"Import"** at the bottom to execute the SQL and set up all the necessary tables.

5.  **Configure the Database Connection**:
    *   Locate the PHP configuration files (likely within `login_system/` or `register_system/` folders, or a root config file like `config.php`).
    *   Update the database credentials (database name, username, password) to match your DerServer setup. The default username for DerServer is often `root` with an empty password.

6.  **Run the Application**:
    *   Open your web browser and navigate to the project's URL, e.g., `http://localhost/Student_Work_Mangement_System/`.

## 🎥 Demo Video

A demonstration of the system is available on YouTube.

[![Watch the demo video](https://img.youtube.com/vi/Wtyr2uiE3wU/0.jpg)](https://www.youtube.com/watch?v=Wtyr2uiE3wU)

*Click the image above to watch the demo.*

## 📄 License

This project is open-source. You can check the repository for any specific license file. If none exists, it's generally understood that you can view and fork the code. For any other use, please contact the repository owner.

## 📬 Contact

Feel free to reach out via my [GitHub profile](https://github.com/LeoTheAuJai) or connect with me through the contact options there.

---
```
```
## 📄 **README.md (中文版)**

```markdown
# 🎓 學生佳作管理系統
```
[![YouTube 示範](https://img.shields.io/badge/示範-YouTube 觀看-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=Wtyr2uiE3wU)

這是一個基於 **PHP** 和 **phpMyAdmin (MySQL)** 的網頁版**學生佳作管理系統**。它旨在管理和展示優秀的學生專題作品，並為不同的使用者角色提供相應的存取權限。

## ✨ 主要功能

*   **三種使用者角色**：系統支援**訪客**、**學生**和**老師**三種角色，各有特定權限。
    *   **訪客**：可以瀏覽公開的佳作與資訊。
    *   **學生**：可以提交自己的作品，並管理個人資料。
    *   **老師**：擁有管理權限，可以審核、管理所有投稿作品及使用者。
*   **佳作展示平台**：提供一個專門的空間來展示和整理優秀的學生作品。
*   **安全存取控制**：包含登入/註冊系統，以管理不同使用者的存取權。
*   **檔案管理功能**：支援與作品相關的檔案上傳和管理。
*   **即時通訊**：（從專案背景推測）可能包含訊息或通知功能。

## 🛠️ 使用技術

*   **前端**：HTML, CSS, JavaScript
*   **後端**：PHP
*   **資料庫**：MySQL（經由 phpMyAdmin 管理）
*   **其他**：AJAX, jQuery
*   **伺服器環境**：專為 **DerServer 17** 設計（或任何支援 PHP 的本機伺服器）

## 🚀 本地安裝指南

按照以下步驟，在你的本機電腦上安裝並執行此專案，以便進行開發或測試。

### 環境需求

*   **DerServer 17**（或其他支援 PHP 和 MySQL 的本機伺服器環境，如 XAMPP、WAMP、MAMP 或 Laragon）
*   **phpMyAdmin**（通常 DerServer 已內建，用於資料庫管理）
*   一個程式碼編輯器，例如 **VS Code**、**Sublime Text** 或 **PHPStorm**
*   一個網頁瀏覽器
*   **Git**（選擇性，用於複製專案）

### 安裝步驟

1.  **取得專案檔案**（複製 repository 或下載 ZIP 檔並解壓縮）。
    ```bash
    git clone https://github.com/LeoTheAuJai/Student_Work_Mangement_System.git
    ```

2.  **將專案資料夾移動**到 DerServer 的根目錄。
    *   **DerServer 17** 的根目錄通常是 `C:\DerServer\htdocs\` 或 `C:\Program Files\DerServer\www\`。請根據你的實際安裝路徑放置。

3.  **啟動 DerServer**：在 DerServer 控制面板中，確保 Apache 和 MySQL 服務都已啟動。

4.  **透過 phpMyAdmin 設定資料庫**：
    *   打開瀏覽器，進入 **phpMyAdmin**（通常網址為 `http://localhost/phpmyadmin` 或 `http://localhost/derphpmyadmin`）。
    *   建立一個新資料庫（例如取名為 `student_work_db`）。
    *   點擊進入剛建立好的資料庫。
    *   選擇上方的 **「匯入 (Import)」** 標籤。
    *   點擊 **「選擇檔案 (Choose File)」**，在專案根目錄中選取 `sms finalized version.sql` 檔案。
    *   點擊最下方的 **「執行 (Go)」** 或 **「匯入 (Import)」**，系統便會建立所有需要的資料表。

5.  **設定資料庫連線**：
    *   找到專案中的 PHP 設定檔（可能位於 `login_system/` 或 `register_system/` 資料夾內，或是根目錄下的 `config.php`）。
    *   根據你的 DerServer 環境，更新檔案中的資料庫連線資訊（資料庫名稱、使用者名稱、密碼）。DerServer 的預設使用者名稱通常是 `root`，密碼為空。

6.  **執行程式**：
    *   打開網頁瀏覽器，在網址列輸入專案的路徑，例如：`http://localhost/Student_Work_Mangement_System/`。

## 🎥 示範影片

系統的操作示範已上傳至 YouTube。

[![觀看示範影片](https://img.youtube.com/vi/Wtyr2uiE3wU/0.jpg)](https://www.youtube.com/watch?v=Wtyr2uiE3wU)

*點擊上方圖片觀看示範。*

## 📄 授權條款

此為開源專案。你可以在 repository 中查看是否有特定的授權檔案。如果沒有，通常意味著你可以檢視和複製程式碼。如需其他用途，請聯絡專案擁有者。

## 📬 聯絡我

歡迎透過我的 [GitHub 個人檔案](https://github.com/LeoTheAuJai) 與我聯繫。

---
```

