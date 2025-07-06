# Bước 1: Tạo môi trường ảo tên là .venv
python -m venv .venv

# Bước 2: Kích hoạt môi trường ảo

# ✅ Trên macOS / Linux:
source .venv/bin/activate

# ✅ Trên Windows:
.venv\Scripts\activate

# Bước 3: Cài đặt thư viện cần thiết từ requirements.txt
pip install -r requirements.txt 
