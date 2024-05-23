# MySeq2SeqTransformer
A real time translator based on Seq2SeqTransformer Model using for my mid-term project in college (HUS)


---------------------------------------------------------------------------------------------------------------------------------
(English below)
Đây là một mô hình dịch thuật sử dụng kiến trúc Transformer với cơ chế attention. Mô hình hiện tại chỉ đang ở mức sơ khai, tác giả sẽ cập nhật phiên bản mới khi có thể :vv

Thông qua mô hình này bạn có thể:

+ Huấn luyện một mô hình học ngôn ngữ
+ Huấn luyện với nhiều ngôn ngữ khác nhau
+ Tìm hiểu thêm về cách thức hoạt động của mô hình ngôn ngữ hiện đại

# Cài Đặt

Ngoài ra, để sử dụng mô hình cần sử dụng nhiều thư viện liên quan. 
Với các nền tảng trực tuyến cần cài đặt
```
 !pip install underthesea
 ```
```
 !pip install tokenizers
```
Với môi trường tích hợp trên máy tính, cần cài đặt
```
 !pip install torch
```
```
!pip install torchtext
```
```
!pip install torchtext.data
```
```
!pip install torchtext.vocab
```
```
!pip install torch.nn
```
```
!pip install torch.utils
```
```
!pip install torch.optim
```
# Mô hình sử dụng

+ Seq2Seq cơ bản
+ Transformer

# Tập dữ liệu

Dữ liệu huấn luyện: https://www.kaggle.com/datasets/hungnm/englishvietnamese-translation
Model checkpoint:
Từ vựng sử dụng: 

# Huấn luyện mô hình

Mô hình sử dụng cơ chế self-attention. Ngoài ra, bạn có thể sử dụng nhiều cơ chế khác nhau:
+ Cơ chế Masked Self Attention
+ Multi-Head Attention
+ Cross-Attention
+ RNN
+ LSTM
+ Vân vân ...

# Hướng dẫn cài đặt

