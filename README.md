## Chủ đề: Nghiên cứu và phát triển hệ thống gợi ý khách sạn và tour du lịch cho trang web đặt phòng
***Cụ thể*
### - Nghiên cứu các thuật toán gợi ý gồm có Memory-based và Model-based dành cho kỹ thuật Lọc cộng tác(Collaborative filtering)
### - Nghiên cứu xây dựng Tour du lịch bằng Lộ trình di chuyển tối ưu

***Thực hiện các bước xây dựng bài toán bằng Code*
| Trình tự thực hiện | Tên các bước                                                      | Link code                                                    |
| ----- | ------------------------------------------------------------                   | ------------------------------------------------------------ |
| 1     |Crawl Data trang web (expedia.com) để lấy dữ liệu về thông tin các khách sạn tại New York | [👆](https://drive.google.com/file/d/18HuhHB5r9GuYalXjfRkR32d-TW838Jx9/view?usp=sharing) |
| 2     |Crawl Data trang web (expedia.com) để lấy dữ liệu về thông tin các khách hàng đã đánh giá các khách sạn tại New York | [👆](https://drive.google.com/file/d/1t8i3_x6wCIGNYJB3WDdWY4KnVZn2MNGQ/view?usp=sharing) |
| 3     |Clean Data dữ liệu "Hotel_NewYork" | [👆](https://drive.google.com/file/d/1sOEHoefHrOApV-JaABjkU9fqjOBTHx5I/view?usp=sharing) |
| 4     |Clean Data dữ liệu "User_NewYork" | [👆](https://drive.google.com/file/d/1mqfDfkgXIqBAXiV6w-KMklLhG0GhJ_ka/view?usp=sharing) |
| 5     |Build SVD Model CF (Lọc cộng tác)  | [👆](https://drive.google.com/file/d/1K8iLC0ASkdo1iL3QwkthujF4tHXzVN6l/view?usp=sharing) |
| 6     |Build Tour bằng lộ trình di chuyển tối ưu sử dụng thư viện “geopy.geocoders”   | [👆](https://drive.google.com/file/d/1oGCeKMrIS4wsMorOyV5SLAnORkW4Nfvh/view?usp=sharing) |

***Việc xây dựng mô hình Lọc cộng tác (CF) dựa vào SVD nhằm*
#### 1. Giảm dung lượng bộ nhớ, giảm kích thước dữ liệu
#### 2. Tìm ra được các tính chất ẩn giữa các users - items. Trong hệ thống gợi ý khách sạn này, tính chất ẩn có thể là sự tiện nghi của khách sạn hay là thái độ phục vụ,… 
#### 3. Thực hiện đề xuất các khách sạn có những tính chất ẩn phù hợp với khách hàng
***Việc xây dựng Tour du lịch bằng lộ trình di chuyển tối ưu nhằm*
#### 1. Xác định các địa điểm du lịch nổi bật, các nhà hàng trong khu vực gần khách sạn mà khách hàng đã lựa chọn.
#### 2. Sắp xếp lộ trình sao cho thời gian đi lại giữa các điểm du lịch được tối ưu, làm giảm chi phí di chuyển và đảm bảo khách hàng có thời gian tham quan đầy đủ mỗi địa điểm.
#### 3. Lựa chọn phương tiện di chuyển phù hợp cho khách hàng.


