# Popularity-Factors-Analysis_-Anime (Phân tích các yếu tố ảnh hưởng đến mức độ phổ biến của Anime)

**📊Project Overview - Mô tả dự án**

(EN)
This project analyzes the _top_anime_dataset.csv_, which contains information about anime released over many years.
The goal is to explore what characteristics make anime more popular, better rated, or more widely appreciated by the community.
The analysis includes exploratory data analysis (EDA), distribution understanding, popularity ranking, rating comparison, and trend analysis.

(VI)

Dự án này phân tích bộ dữ liệu top_anime_dataset.csv, chứa thông tin về các bộ anime được phát hành qua nhiều năm.
Mục tiêu là khám phá những đặc điểm ảnh hưởng đến sự phổ biến, mức độ yêu thích và đánh giá của cộng đồng đối với từng anime.
Phân tích bao gồm EDA, phân bố dữ liệu, xếp hạng độ phổ biến, so sánh điểm đánh giá, và xu hướng phát hành theo thời gian.

**📂 Dataset | Nguồn dữ liệu**

(EN)
The dataset is provided for academic purposes by the University of Science (VNU-HCM).
The dataset includes:
- Basic anime metadata (title, type, episodes, premiered year)
- Popularity-related metrics (favorites, members, watching)
- Quality-related metrics (score, ranked)
- Genre and classification attributes
  
(VI)
Dữ liệu được cung cấp cho mục đích học thuật bởi Trường Đại học Khoa học Tự nhiên – ĐHQG TP.HCM.
Bộ dữ liệu bao gồm:
- Thông tin chung của anime (tên phim, loại hình, số tập, năm phát hành)
- Các chỉ số về độ phổ biến (favorites, members, watching)
- Các chỉ số chất lượng (score, ranked)
- Thể loại và phân loại nội dung

**⭐ Project Objectives - Mục tiêu dự án**

(EN)

✔ Understand the structure and basic characteristics of the dataset

✔ Analyze distributions and outliers across all variables

✔ Identify the Top 10 most “favorited” anime

✔ Compare average scores by anime type

✔ Explore release trends over the years

✔ Determine which genres receive the highest community scores

(VI)

✔ Tìm hiểu cấu trúc và đặc điểm cơ bản của bộ dữ liệu

✔ Phân tích phân bố và outlier của từng biến

✔ Xác định Top 10 anime có lượt yêu thích cao nhất

✔ So sánh điểm đánh giá trung bình theo loại anime

✔ Phân tích xu hướng phát hành qua từng năm

✔ Xác định thể loại anime được cộng đồng đánh giá cao nhất

**🔎 Methodology | Quy trình thực hiện**

Step 1: Data Exploration 

<img width="200" height="400" alt="image" src="https://github.com/user-attachments/assets/7b286edc-fda1-4cff-9bd7-f44238b32e77" />

Step 2: Univariate Analysis
- Unique count, missing values, outlier detection
- Histograms, boxplots, KDE plots
- 
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/f1039fa4-478d-4d0a-82f3-5eac302748cd" />

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/081c1ae4-f92a-4cda-bae9-317885ca2be4" />
<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/96373eb9-8450-49a6-8402-0892c49a818f" />
<img width="1000" height="400" alt="image" src="https://github.com/user-attachments/assets/5cf440cc-48b5-4b22-9efd-881fc82ceac6" />

Step 3: Exploratory Data Analysis & Visualization

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/8385ce60-7482-426b-bfc6-b3ad472a8c3f" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/1b9f90d6-64a3-4054-b5d6-76903c176f64" />
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/d76d5d66-0329-472a-9e18-d441b746b989" />
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/a7594084-71d9-400c-9d24-b7a83bc52745" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/04052c6c-1b0c-4373-a904-42b79d877868" />

**🧩 Key Insights**

(EN)
- The dataset contains many missing fields — cleaning is required for reliable analysis.
- Titles like One Piece and Death Note have huge fanbases despite not having top scores → strong brand legacy.
- TV (6.92) and Movie (6.82) formats score the highest → stronger production and storytelling.
- CM, Music, PV Have Lower Ratings: Scores < 6.4 — likely due to short or promotional nature.
- Strong Growth Trend in Anime Releases: Sharp growth between 2010–2020, slight decline post-2020 due to Covid-19.
- Award-winning titles average 7.45 → high-quality and well-produced.
- Best-Rated Genres: Suspense, Mystery, Drama, Romance (Scores range 6.92–7.22)
- Action & Adventure: Popular but Lower Scores: Scores 6.8–6.9 — widely watched but with simpler narratives.

(VN)
- Bộ dữ liệu có nhiều giá trị bị thiếu — cần xử lý, làm sạch để đảm bảo phân tích chính xác.
- Các tựa anime như One Piece và Death Note có lượng fan khổng lồ dù không có điểm cao nhất → cho thấy sức mạnh thương hiệu.
- Hai định dạng TV (6.92) và Movie (6.82) có điểm đánh giá cao nhất → chất lượng nội dung và sản xuất vượt trội.
- CM, Music, PV có điểm thấp hơn (dưới 6.4) — khả năng do thời lượng ngắn hoặc mang tính quảng bá.
- Xu hướng phát hành anime tăng mạnh giai đoạn 2010–2020, giảm nhẹ sau 2020 do ảnh hưởng Covid-19.
- Các anime đạt giải thưởng có điểm trung bình 7.45 → phản ánh chất lượng sản xuất cao.
- Các thể loại được đánh giá tốt nhất: Suspense, Mystery, Drama, Romance (điểm từ 6.92–7.22).
- Action & Adventure: phổ biến nhưng điểm đánh giá thấp hơn (6.8–6.9) — thường có cốt truyện đơn giản hơn.

**💼 6. Business Recommendations | Đề Xuất Phát Triển**

(EN)

1. Strengthen Key Franchises: Leverage major franchises such as One Piece to expand spin-offs, films, and merchandise.
2. Prioritize TV & Movie Production: TV and Movie formats consistently score the highest → keep these as top investment priorities.
3. Enhance CM, Music, PV Quality: Increase narrative depth and artistic direction to improve viewer reception.
4. Align Releases With Peak Trends: Optimize release schedules based on historical high-demand periods.
5. Expand High-Rated Genres:Invest more in high-performing genres such as Suspense, Mystery, Drama, and Romance.
6. Improve Action & Adventure Storylines: Enhance storytelling complexity to elevate audience ratings.

(VN)
1. Tăng Cường Khai Thác Các Thương Hiệu Lớn: Tận dụng sức mạnh thương hiệu như One Piece để phát triển spin-off, movie và merchandise.
2. Ưu Tiên Đầu Tư TV & Movie: TV và Movie là hai loại có điểm đánh giá cao nhất → nên tiếp tục đầu tư mạnh.
3. Nâng cao Chất Lượng CM, Music, PV: Bổ sung storytelling và chiều sâu nghệ thuật để cải thiện đánh giá.
4. Tối Ưu Lịch Phát Hành Theo Xu Hướng: Điều chỉnh thời điểm phát hành dựa trên các giai đoạn nhu cầu tăng cao.
5. Mở Rộng Các Thể Loại Được Đánh Giá Cao: Tập trung phát triển thêm anime thuộc Suspense, Mystery, Drama và Romance.
6. Cải Thiện Nội Dung Action & Adventure: Xây dựng cốt truyện sâu sắc hơn để nâng cao điểm đánh giá tổng thể.
7. 
**⭐ 7. Tools & Technologies**

(EN)

- Python (Pandas, NumPy)

- Matplotlib & Seaborn (visualization)

- Jupyter Notebook/ VS code

**🚀 Project Links | Liên kết dự án**

💻 GitHub (Code):
[https://github.com/anhthuong127/
](https://github.com/anhthuong127/Popularity-Factors-Analysis_-Anime/)

📂 Cleaned Data:
[https://drive.google.com/drive/folders/1I-GiRSyvC9FNxTpFroYZ189g_n3JNDEY
](https://drive.google.com/drive/folders/1r1dBwWXyG1xA4pJVuHid-gK3HeBX6UCc)

👩‍💻 Author
Anh Thuong Tran - Data Analyst
LinkedIn: https://www.linkedin.com/in/trananhthuong/




