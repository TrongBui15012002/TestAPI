# TestAPI
1. Lấy danh sách user: GET https://reqres.in/api/users?page=2
- Chức năng: Lấy danh sách user có sẵn trong hệ thống ở trang số 2
- Tham số: Không có
- Kết quả trả về: 1 file JSON chứa các user, mối user có các thuộc tính như: "id", "email", "firstname", "lastname", "avata"
- Test kết quả trả về: Trạng thái trả về, thời gian phản hồi, trang hiện tại và tổng số user có trong danh sách
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/eab8eccd-14d4-44ca-87fe-03fb87cbb827)
2. Lấy 1 user trong danh sách user: GET https://reqres.in/api/users/2
- Chức năng: Lấy một user có sẵn trong hệ thống với id là 2
- Tham số: Không có
- Kết quả trả về: 1 file JSON chứa user có id là 2 với các thuộc tính: "id", "email", "firstname", "lastname", "avata"
- Test kết quả trả về: Trạng thái trả về, thời gian phản hồi và id của user
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/18ba033f-4f4f-4b9a-87e1-8a5fe4ce2181)
3. Lấy một user không tồn tại trong danh sách user: GET https://reqres.in/api/users/23
- Chức năng: Lấy một user không có trong hệ thống với id là 23
- Tham số: Không có
- Kết quả trả về: rỗng
- Test kết quả trả về: Trạng thái trả về, thời gian phản hồi
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/6a86360e-8c87-4424-9ab2-21778efd0d7c)
4. Tạo một user mới: POST https://reqres.in/api/users
- Chức năng: Tạo một user mới
- Tham số: Dữ liệu JSON chứa thuộc tính: "name", "job" của user mới
- Kết quả: File JSON chứ thông tin của user vừa tạo gồm: "name", "job", "id", "createdAt"
- Test kết quả trả về: Trạng thái trả về, thời gian phản hồi
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/17f9febc-8640-4f20-a51f-149a39d3f68d)
5. Lấy một danh sách user ở trang bất kỳ: GET https://reqres.in/api/unknown
- Chức năng: Lấy danh sách API ở trang bất kì
- Tham số: Không có
- Kết quả: File JSON chứ danh sách user ở page 2
- Test kết quả trả về: trạng thái trả về, thời gian phản hồi
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/e023b1c2-678e-49d6-a4f4-6c4fb3426b9c)
6. Lấy thông tin user bất kỳ có id là 2: GET https://reqres.in/api/unknown/2
- Chức năng: Lấy thông tin 1 user có id là 2
- Tham số: Không có
- Kết quả: File JSON chứa thông tin của user có id là 2
- Test kết quả trả về: trạng thái trả về, thời gian phản hồi
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/14e6c47a-f301-46fb-a5f4-049fc178a74a)
7. Update thông tin của một user xác định: PUT https://reqres.in/api/users/2
- Chức năng: Sửa đổi thông tin của user có id là 2
- Tham số: File JSON chứa thông tin cần sửa
- Kết quả: Thông tin của user có id là 2 sau khi đã sửa
- Test kết quả trả về: Trạng thái trả về, thời gian phản hồi
- ![image](https://github.com/TrongBui15012002/TestAPI/assets/91036603/19683f43-4aee-451c-aa91-ef9110f296b5)
8. Xoá một user xác định: DELETE https://reqres.in/api/users/2
- Chức năng: Xoá user có id là 2
- Tham số: Không có
- Kết quả: rỗng
- Test kết quả trả về: Trạng thái trả về
- https://reqres.in/api/users/2






