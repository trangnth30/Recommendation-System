# Thành viên thực hiện

## **Giảng viên hướng dẫn**
- **Th.S Huỳnh Văn Tín**

## **Nhóm sinh viên thực hiện**
- **Nguyễn Ngọc Yến Nhi**
- **Nguyễn Đức Anh**
- **Nguyễn Thị Huyền Trang**

## **Môn học:***  DS300.P11 - Hệ khuyến nghị
# ViNewRec: Bộ Dữ Liệu Tin Tức Xã Hội Tiếng Việt Chất Lượng Cao

## Giới thiệu

ViNewRec là một bộ dữ liệu tiếng Việt chất lượng cao, được thiết kế để hỗ trợ các hệ thống gợi ý tin tức dựa trên nội dung và cộng tác. Bộ dữ liệu này tích hợp cả nội dung bài báo và thông tin tương tác người dùng, giúp cải thiện các mô hình đề xuất cá nhân hóa và nghiên cứu xử lý ngôn ngữ tự nhiên (NLP).

Bộ dữ liệu được thu thập từ nền tảng báo điện tử VnExpress, bao gồm các bài viết thuộc nhiều lĩnh vực như kinh tế, khoa học, giáo dục, công nghệ, văn hóa, và xã hội, cùng với hàng chục nghìn bình luận của người dùng.

## Các đặc điểm chính của ViNewRec

- **Dữ liệu đa dạng**: Chứa thông tin từ nhiều lĩnh vực khác nhau, phản ánh sự quan tâm của người đọc đối với các chủ đề khác nhau.
- **Tích hợp tương tác người dùng**: Bao gồm dữ liệu về lượt đọc, chia sẻ, bình luận, giúp nghiên cứu các hệ thống gợi ý dựa trên hành vi người dùng.
- **Hỗ trợ NLP**: Được xử lý và chuẩn hóa để phù hợp với các mô hình học máy và xử lý ngôn ngữ tự nhiên.
- **Ứng dụng hệ thống gợi ý**: Được sử dụng để phát triển và đánh giá các mô hình gợi ý tin tức cá nhân hóa.

## Các nhiệm vụ nghiên cứu chính

ViNewRec hỗ trợ hai chiến lược gợi ý chính:

1. **Gợi ý dựa trên nội dung (Content-Based Recommendation)**  
   - Sử dụng các mô hình ngôn ngữ tiên tiến như PhoBERT, XLM-R, Meta-LLaMA để biểu diễn bài viết và tương tác người dùng.
   - Kết quả thực nghiệm cho thấy Meta-LLaMA đạt Precision@1 cao nhất (0.3290), vượt Baseline PhoBERT 18.4%.

2. **Gợi ý dựa trên cộng tác (Collaborative Filtering)**  
   - Áp dụng mô hình Neural Collaborative Filtering (NCF) kết hợp với thông tin văn bản để cải thiện độ chính xác.
   - Mô hình Text-based NeuCF cho kết quả Recall và Precision cao hơn mô hình NeuCF cơ bản tại top@5 và top@10.

## Hướng phát triển

- **Mở rộng tập dữ liệu**: Bổ sung hình ảnh, video và các yếu tố đa phương tiện để hỗ trợ nghiên cứu hệ thống gợi ý tin tức đa phương thức.
- **Cải thiện mô hình**: Nâng cấp các mô hình gợi ý, kết hợp các mô hình ngôn ngữ lớn để tối ưu hiệu suất.
- **Khắc phục thiên lệch**: Áp dụng các phương pháp giảm bias trong hệ thống gợi ý nhằm nâng cao trải nghiệm người dùng.
