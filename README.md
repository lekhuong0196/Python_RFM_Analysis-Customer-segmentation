# Python_RFM_Analysis-Customer-segmentation
I. INTRODUCTION
1. About RFM Analysis
Why RFM?
•	RFM (Recency, Frequency, Monetary) analysis is a marketing model using customer segmentation based on their transaction history.
•	This model could be very useful, especially for small and medium-sized enterprises (SMEs) with limited marketing resources, helping them focus on the potentially right customer segments to increase ROI, reduce churn, reduce cost, improve customer relationship, and a lot more.
How?
•	In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores.
Reference:
•	https://www.putler.com/rfm-analysis
2. Dataset
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
•	InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
•	StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
•	Description: Product (item) name. Nominal.
•	Quantity: The quantities of each product (item) per transaction. Numeric.
•	InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
•	UnitPrice: Unit price. Numeric, Product price per unit in sterling.
•	CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
•	Country: Country name. Nominal, the name of the country where each customer resides.
 
3. RFM model
•	RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries
•	RFM stands for the three dimensions:
i.	Recency – How recently did the customer purchase?
ii.	Frequency – How often do they purchase?
iii.	Monetary Value – How much do they spend?
•	RFM analysis numerically ranks a customer in each of these three categories, generally on a scale of 1 to 5 (the higher the number, the better the result). The “best” customer would receive a top score in every category.
 
3. Dưới đây là một số câu hỏi kinh doanh quan trọng mà mô hình phân khúc FRM có thể giúp doanh nghiệp giải đáp:
1. Phân khúc khách hàng nào có tiềm năng sinh lời cao nhất?
Phân tích điểm RFM của khách hàng có thể giúp doanh nghiệp xác định phân khúc khách hàng có khả năng chi tiêu nhiều nhất trong tương lai. Doanh nghiệp có thể tập trung nguồn lực marketing và bán hàng vào phân khúc khách hàng này để tối ưu hóa lợi nhuận.
2. Nên triển khai chương trình tiếp thị nào cho từng phân khúc khách hàng?
Doanh nghiệp có thể thiết kế các chương trình tiếp thị phù hợp với nhu cầu, sở thích và hành vi mua hàng của từng phân khúc khách hàng. Ví dụ:
•	Đối với khách hàng tiềm năng: Doanh nghiệp có thể cung cấp các chương trình khuyến mãi và giảm giá để thu hút họ mua hàng lần đầu tiên.
•	Đối với khách hàng mới: Doanh nghiệp có thể gửi email chào mừng và giới thiệu các sản phẩm hoặc dịch vụ mới.
•	Đối với khách hàng thường xuyên: Doanh nghiệp có thể cung cấp các chương trình tri ân và ưu đãi đặc biệt để giữ chân họ.
•	Đối với khách hàng VIP: Doanh nghiệp có thể cung cấp dịch vụ khách hàng cao cấp và các chương trình độc quyền.
3. Làm thế nào để theo dõi hiệu quả của các chương trình tiếp thị được triển khai cho từng phân khúc khách hàng?
Doanh nghiệp cần theo dõi các chỉ số hiệu suất chính (KPI) để đánh giá hiệu quả của các chương trình tiếp thị được triển khai cho từng phân khúc khách hàng. Một số KPI quan trọng bao gồm:
•	Tỷ lệ chuyển đổi: Tỷ lệ khách hàng thực hiện hành động mong muốn, ví dụ như mua hàng, đăng ký nhận bản tin, v.v.
•	Giá trị đơn hàng trung bình: Số tiền trung bình mà khách hàng chi tiêu cho mỗi đơn hàng.
•	Tỷ lệ giữ chân khách hàng: Tỷ lệ khách hàng tiếp tục mua hàng của doanh nghiệp trong một khoảng thời gian nhất định.
4. Làm thế nào để cải thiện hiệu quả của mô hình phân khúc FRM?
Doanh nghiệp có thể cải thiện hiệu quả của mô hình phân khúc FRM bằng cách:
•	Sử dụng nhiều nguồn dữ liệu: Kết hợp dữ liệu mua hàng từ nhiều nguồn khác nhau, chẳng hạn như hệ thống POS, trang web, ứng dụng di động, v.v., để có được bức tranh toàn diện hơn về hành vi mua hàng của khách hàng.
II. DATA VISUALIZATION WITH PYTHON
Distribution chart for each variable of the model

   Treemap of RFM segments of customer count 
Treemap of RFM segments of customer count 
III. INSIGHTS
•	2 segments with the highest proportion of customers are Champions (19.21%) and Hibernating custumers (16.28%)
•	Negative segments such as Hibernating and Lost accounted for a high proportion of customers, 16.28% and 11.15%, respectively. However, these two groups account for less than 8% of total sales
•	The two most positive segments both account for a high proportion of total sales (Champion (60.88%) and Loyalty (11.89%). This is a good sign for the company and in upcoming marketing campaigns, the company needs to have campaigns to maintain and develop this customer segment.
IV. RECOMMENDATIONS
•	The company needs to have policies to:
•	Positive customers:
	For new customers who have made a recent purchase, send a personalized welcome email or offer that thanks them for their purchase and encourages them to return to our business.
	For customers who have made a high-value purchase ( Champions, loyar), thank them for their business and offer a loyalty program that rewards them for their continued purchases.
•	Negative customers:
	For hibernating customers who have not made a purchase in a while, send a win-back email or offer that encourages them to return to our business.
	For customers who have made multiple purchases in the past but have not made one recently, send personalized email campaigns that showcase new products or services that may be of interest to them.
	For high-value customers who have not made a purchase in a while, send a personalized email or offer that highlights new products or services that may be of interest to them and offer a special discount or promotion that is tailored to their past purchase history.


