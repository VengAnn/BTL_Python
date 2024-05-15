Make by: KUN VENG ANN - 56KMT - CPC205013 - TNUT

THEO DÕI TOP 10 MOVIE(BỘ PHIM) NỔI TIẾNG
1. Cơ sở dữ liệu:
- Bảng:
    movies: Lưu thông tin về bộ phim, bao gồm movie_id (PK), title,vote_average (bỏ phiếu trung bình),image.
- Stored Procedures (SP_GETTopTenMovies):
    SP_GETTopTenMovies: Lấy thông tin của 10 tên bộ phim nối tiếng.
2. Module đọc dữ liệu:
    Sử dụng Python và FastAPI để tạo một API để lấy dữ liệu từ trang web chuyên về movie hoặc dịch vụ API thương mại như themoviedb
3. Mô tả nguồn dữ liệu:
Có thể sử dụng Web Scraping hoặc lấy dữ liệu qua API của các trang web chuyên về phim.
Dữ liệu bao gồm thông tin về bộ phim và điểm đánh giá từ người dùng.
4. Node-RED:
Xây dựng một chu trình trong Node-RED để tự động gọi API Python để lấy dữ liệu. Sau đó, xử lý dữ liệu và ghi vào cơ sở dữ liệu.
5. Web:
+ Hiển thị danh sách các bộ phim và điểm đánh giá của chúng:
Tạo một trang web với danh sách các bộ phim.
Mỗi bộ phim sẽ hiển thị tên và điểm đánh giá của nó.
Có thể sử dụng HTML và CSS để tạo giao diện đơn giản và hấp dẫn.
+ Biểu đồ cột cho các bộ phim nổi tiếng:
Tạo một biểu đồ cột để hiển thị điểm đánh giá của các bộ phim.
Các cột sẽ biểu diễn điểm đánh giá của từng bộ phim.
Sử dụng JavaScript và một thư viện biểu đồ như Chart.js để tạo và hiển thị biểu đồ.

