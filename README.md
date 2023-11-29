# myrecommender
## Raw data
Dữ liệu raw của tập dữ liệu MovieLens được lưu trong [folder](data). Tập dữ liệu sử dụng để thực nghiệm là movielens_1M

## Enrich data
### Dữ liệu được tiền xử lý theo luồng sau:
- Chuyển dữ liệu về dạng `.csv` và lưu vào folder [enrich](enrich)
- Thay đổi movieid dựa trên index của tập dữ liệu [movies.csv](enrich\movies.csv)
- Tạo ma trận features matrix bằng TF-IDF để thực hiện recommendation theo hướng cơ bản nhất theo phương pháp content-based

## Deep Learning & Recommendation Systems
### KNN
Sử dụng KNN để thực hiện xây dựng hệ khuyến nghị

### Deep Learning
Dùng model LightGCN để xây dựng hệ khuyến nghị
(Giải thích thêm về mô hình)

## Visualize
... (Hình ảnh trực quan)


## Deploy ứng dụng

