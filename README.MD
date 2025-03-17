# Hướng dẫn sử dụng dự án

Tài liệu này cung cấp hướng dẫn chi tiết về cách cài đặt, cấu hình và chạy dự án này.

## Clone dự án từ GitHub

```bash
git clone https://github.com/baolamabcd13/jupyter-lmt.git
```

## Cài đặt thư viện

1. Tạo và kích hoạt môi trường ảo:

```bash
# Tạo môi trường ảo
python -m venv venv

# Kích hoạt môi trường ảo
# Trên Windows:
venv\Scripts\activate
```

2. Cài đặt các thư viện cần thiết:

```bash
pip install -r requirements.txt
```

## Chạy dự án

### Chạy Jupyter Notebook

1. Kích hoạt môi trường ảo (nếu chưa kích hoạt)
2. Chạy Jupyter Notebook:

```bash
jupyter notebook
```

3. Trình duyệt sẽ tự động mở với giao diện Jupyter. Điều hướng đến thư mục `notebooks` và mở file `renew.ipynb`.

## Cấu trúc dự án

Dưới đây là mô tả về các thành phần chính trong dự án:

### Notebooks

- `notebooks/renew.ipynb`: Notebook chính chứa mã phân tích dữ liệu và các kết quả. Notebook này thực hiện phân tích và xử lý dữ liệu.

### Dữ liệu

- `data/`: Thư mục chứa các tập dữ liệu được sử dụng trong dự án.

### Hình ảnh

- `reports/`: Thư mục chứa các hình ảnh đồ thị
