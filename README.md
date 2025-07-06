# Bước 1: Tạo môi trường ảo tên là .venv
python -m venv .venv

# Bước 2: Kích hoạt môi trường ảo

# ✅ Trên macOS / Linux:
source .venv/bin/activate

# ✅ Trên Windows:
.venv\Scripts\activate

# Bước 3: Cài đặt thư viện cần thiết từ requirements.txt
pip install -r requirements.txt

# (Hoặc cài từng thư viện nếu chưa có requirements.txt)
# pip install numpy pandas ...

# Bước 4 (tuỳ chọn): Lưu lại các thư viện vào requirements.txt
pip freeze > requirements.txt

# Bước 5: Khi dùng xong, thoát môi trường ảo
deactivate
