# Recommendation System for Be Beauty

## Content
1. [Recommendation System](#Recommendation-System)

   1.1 [Định nghĩa](#Định-nghĩa)

   1.2 [Các thành phần cơ bản](#Các-thành-phần-cơ-bản)

   1.3 [Hướng tiếp cận](#Hướng-tiếp-cận)

1. [CONTENT-BASED FILTERING RECOMMENDERS VÀ COLLABORATIVE FILTERING RECOMMENDERS](#CONTENT-BASED-FILTERING-RECOMMENDERS-VÀ-COLLABORATIVE-FILTERING-RECOMMENDERS)
1. [Ý tưởng cho Be Beauty](#Ý-tưởng-cho-Be-Beauty)

# Recommendation System
### Định nghĩa
Recommendation System (Recommender System) là một dạng của hệ hỗ trợ ra quyết định, cung cấp giải pháp mang tính cá nhân hóa mà không phải trải qua quá trình tìm kiếm phức tạp. Recommendation System học từ người dùng và gợi ý các sản phẩm tốt nhất trong số các sản phẩm phù hợp.

Recommendation System sử dụng các tri thức về sản phẩm, các tri thức của chuyên gia hay tri thức khai phá học được từ hành vi con người dùng để đưa ra các gợi ý về sản phẩm mà họ thích trong hàng ngàn hàng vạn sản phẩm có trong hệ thống.

Các sản phẩm được gợi ý dựa trên số lượng sản phẩm đó đã được bán, dựa trên các thông tin cá nhân của người sử dụng, dựa trên sự phân tích hành vi mua hàng trước đó của người sử dụng để đưa ra các dự đoán về hành vi mua hàng trong tương lai của chính khách hàng đó.

Các dạng gợi ý bao gồm: 
- Gợi ý các sản phẩm tới người tiêu dùng, 
- Các thông tin sản phẩm mang tính cá nhân hóa, 
- Tổng kết các ý kiến cộng đồng, 
- Cung cấp các chia sẻ, các phê bình, đánh giá mang tính cộng đồng liên quan tới yêu cầu, mục đích của người sử dụng đó.

### Các thành phần cơ bản:

- Thứ nhất: Điều đầu tiên cần phải quan tâm đó chính là ***Người dùng (User)***, hiển nhiên rồi, nếu không có user thì chúng ta biết gợi ý cho ai.

- Thứ hai: Chúng ta cần phải quan tâm đến các mục tin (Items) - các mục tin này có thể là sản phẩm trên các trang bán hàng, bài hát trên các trang nghe nhạc,…

- Thứ ba: Chúng ta cần phải quan tâm đến phản hồi (feedback) của mỗi user lên mục tin đó. Nó có thể là điểm đánh giá, có thể là một chỉ số thể hiện sự quan tâm của user lên item đó....

### Hướng tiếp cận:

Bước 1: Tìm các đặc trưng (features) có ảnh hưởng đến việc đánh giá của người dùng, thông qua việc phân tích và thăm dò dữ liệu.

Bước 2: Phân tích và áp dụng giải thuật filtering phù hợp.

Bước 3: Tiến hành training mô hình.

<p align="center">
   <img src="https://drive.google.com/file/d/14P2hY8cV9bFiGM4SqB6IkyqryXkBShvi/view?usp=sharing">
</p>
 
