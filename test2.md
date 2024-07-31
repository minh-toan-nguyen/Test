Để thêm tệp Markdown (.md) vào một repo trên GitHub, bạn có thể làm theo các bước sau:

### Sử dụng GitHub Web Interface

1. **Đăng nhập vào GitHub và điều hướng đến repo của bạn:**
   - Mở trình duyệt và đăng nhập vào tài khoản GitHub của bạn.
   - Điều hướng đến repo mà bạn muốn thêm tệp.

2. **Tạo tệp mới:**
   - Nhấp vào nút "Add file" (Thêm tệp) ở góc phải phía trên của trang repo.
   - Chọn "Create new file" (Tạo tệp mới).

3. **Đặt tên và thêm nội dung cho tệp:**
   - Nhập tên tệp với phần mở rộng `.md` (ví dụ: `README.md`, `document.md`).
   - Viết nội dung Markdown vào khung soạn thảo.

4. **Commit tệp mới:**
   - Cuộn xuống và nhập thông tin commit trong mục "Commit new file" (Commit tệp mới).
   - Nhấp vào nút "Commit new file".

### Sử dụng Git Command Line

1. **Clone repo về máy tính:**
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```

2. **Tạo tệp Markdown:**
   - Sử dụng trình soạn thảo văn bản của bạn để tạo tệp Markdown mới và lưu tệp với phần mở rộng `.md`. Ví dụ: `document.md`.

3. **Thêm tệp vào repo:**
   ```bash
   git add document.md
   ```

4. **Commit thay đổi:**
   ```bash
   git commit -m "Thêm tệp document.md"
   ```

5. **Push thay đổi lên GitHub:**
   ```bash
   git push origin main
   ```

   Thay `main` bằng tên nhánh mà bạn đang làm việc nếu không phải là `main`.

### Sử dụng GitHub Desktop

1. **Clone repo về máy tính:**
   - Mở GitHub Desktop và đăng nhập.
   - Chọn "Clone a repository from the Internet..." và nhập URL của repo.

2. **Tạo tệp Markdown:**
   - Sử dụng trình soạn thảo văn bản để tạo tệp Markdown mới và lưu tệp với phần mở rộng `.md`.

3. **Thêm và commit tệp:**
   - Mở GitHub Desktop.
   - Bạn sẽ thấy tệp mới trong danh sách các thay đổi. Đảm bảo tệp được chọn.
   - Nhập thông tin commit và nhấp vào nút "Commit to main" (hoặc tên nhánh khác nếu cần).

4. **Push thay đổi lên GitHub:**
   - Nhấp vào nút "Push origin" để đẩy thay đổi lên GitHub.

Với những cách trên, bạn có thể dễ dàng thêm tệp Markdown vào repo của mình trên GitHub.
