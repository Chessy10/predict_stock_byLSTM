# Dự đoán giá cổ phiếu bằng cách sử dụng mô hình Long Short Term Memory - LSTM
# Long Short Term Memory - LSTM
Một mô hình học máy khá phổ biến trong lĩnh vực học sâu. 

Mạng bộ nhớ dài–ngắn( Long Short Term Memory networks) thường được gọi là LSTM – là một dạng đặc biệt của RNN, có khả năng học được các phụ thuộc xa. Được giới thiệu bởi Hochreiter & Schmidhuber (1997), sau đó đã được cải tiến và phát triển đến ngày hôm nay.
LSTM được thiết kế để khắc phục được vấn đề đã xảy ra với RNN trước đó vấn đề phụ thuộc xa (long-term dependency). Việc ghi nhớ thông tin trong suốt thời gian dài là đặc tính mặc định của chúng, chứ ta không cần phải huấn luyện nó để ghi nhớ.
Tức là ngay nội tại của LSTM đã có thể ghi nhớ mà không cần bất kì can thiệp nào. 

# Lấy dữ liệu dự đoán
Ta có thể truy cập "Yahoo Finance" : https://www.bing.com/ck/a?!&&p=65aff92ac9094c88JmltdHM9MTcxODQwOTYwMCZpZ3VpZD0yMzIyZTY2Yi04MmI0LTY5YWUtMzc4NC1mNWM1ODM1ZTY4ZTQmaW5zaWQ9NTE5OQ&ptn=3&ver=2&hsh=3&fclid=2322e66b-82b4-69ae-3784-f5c5835e68e4&psq=yahoo+finance&u=a1aHR0cHM6Ly9maW5hbmNlLnlhaG9vLmNvbS8&ntb=1
Để lấy dữ liệu cần cho mô hình

# Code
**Tôi sử dụng "google colab" để thực hiện dự án này, google colab rất phổ biến cho những người dùng python để sử dụng trong lĩnh vực học máy cũng như học sâu, với việc được cung cấp 1 lượng khá lớn dữ liệu bộ nhớ cho những dự án không quá lớn.

Nguồn code colab của tôi: https://colab.research.google.com/drive/1HBboc_LWkbpRsPc9_UCU0qsNr6Z8DCuw?usp=sharing
