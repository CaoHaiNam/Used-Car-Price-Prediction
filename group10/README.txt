Project sử dụng Python phiên bản 3.8.5-64 bit. 
Chương trình được chạy trên hệ điều hành Ubuntu 20.04. 

Phần 1: cài đặt thư viên
File requirements.txt: tên các thư viện cần được cài đặt.
Cài đặt thư viên bằng câu lệnh trên termimal:
python3 -m pip install -r requirements.txt

Phần 2: crawl dữ liệu
Dữ liệu được crawl trên oto.com, xe.chotot.com,
Dữ liệu thô được lưu trữ trong thư mục dataset, dưới dạng file csv.
Do số lượng page của từng trang web là rất lớn, nên chúng em chỉ thực hiện demo dữ liệu trên số lượng page nhỏ.
Chạy code crawl


Phần 3: Lập trình
Được chia làm 3 file, file tiền xử lý dữ liệu (preprocess.ipynb), file huấn luyện mô hình (train.pynb), và file dự đoán (predict.ipynb).
Các giá trị trong các cell đã được thiết lập sẵn, chỉ cần chạy là được.
