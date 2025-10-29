<h1 align="center">JAVA-28</h1>
<h3 align="center">(T2, T4 21h / T6 22h)</h3>

# 1. Nội quy

- Vào đúng giờ để check in, check out trước khi ra khỏi lớp (nếu xin phép nghỉ sớm cũng phải check out).
- Mở camera trong quá trình tham gia buổi học.
- Trao đổi với giáo viên khi gặp khuất mắt.

# 2. Thông tin khoá học

## 2.1. Lộ trình

- Bám theo lộ trình định sẵn của trung tâm từ chương 4 chương.
- Ngoài ra giao viên có thể tạo 1-2 buổi học đặc biệt / tháng để học những kiến thức ngoài luồng.

## 2.2. Bài tập

- Bài tập theo nhóm chủ đề được học trong lộ trình (bài tập trên web).
- Ngoài ra còn được cung cấp thêm các bài tập tổng ôn toàn khoá (bài tập mở rộng).
- Học viên tự giác làm các bài tập để ôn tập và luyện code.

## 2.3. Buổi học

- Buổi học sẽ được liệt kê các nội dụng thuộc chương cần học để học viên nắm rõ thông tin buổi học.
- Buổi học sẽ được đính kèm tài liệu tham khảo cho các nội dung trong buổi học.
- Sau mỗi buổi học nếu được chỉ định bài tập về nhà thì học viên bắt buộc làm 75% số lượng bài được yêu cầu.

# 3. Công cụ yêu cầu

- Môi trường Java.
    - Window ([LINK](https://download.oracle.com/java/21/latest/jdk-21_windows-x64_bin.exe)).
    - MacOS ([LINK](https://download.oracle.com/java/21/latest/jdk-21_macos-x64_bin.dmg)).

- Công cụ VSCode.
    - Window/MacOS ([LINK](https://code.visualstudio.com/)).

    Ngoài ra có thể dùng các công cụ khác như IntelliJ IDEA, Eclipse, NetBeans như vẫn khuyến khích dùng đồng bộ một công cụ khi tham gia khoá học là VSCode.

# 4. Nội dung học tập

## 4.1. Cơ bản ([LINK](https://www.notion.so/1-Basic-171e3c27ef3781cd8362ec97e0e94250))

- Lệnh in cơ bản.
    - Hàm `println()`.
    - Hàm `print()`.
- Biến và kiểu dữ liệu.
    - Khai báo và khởi tạo biến, định nghĩa biến.
    - Kiểu nguyên thuỷ (kiểu tham trị) và kiểu dữ liệu đối tượng (kiểu tham chiếu).
    - Ép kiểu nguyên thủy (ép kiểu tường minh).
- Nhập liệu.
    - Hàm `nextByte()`, `nextShort()`, `nextInt()`, `nextLong()`, `nextFloat()`, `nextDouble()`, `nextBoolean()`, `next()` và `nextLine()` của chuẩn nhập liệu Scanner.
    - Khác việt giữa hàm nhập liệu `nextLine()` và các hàm nhập liệu còn lại.
- Toán tử.
    - Arithmetic, gồm các toán tử `+, - *, /, %`.
    - Unary, gồm các toán tử Prefix `+, -, ~, !` và Prefix/Postfix `++, --`.
    - Bit, gồm dịch bit (Shift) `>>, <<` và phép toán bit (Bitwise) `&, |, ^`.
    - Logical, gồm các toán tử kết hợp điều kiện `&&, ||`.
    - Assignment, gồm toán tử gán `=` và các toán tử gán gộp `<operator>=.`
    - Relational, gồm toán tử so sánh tham chiếu `==, !=` và toán tử so sánh số `<, >, <=, >=`.
    - Ternary, biểu diễn câu điều kiện có 2 về if-else, có cấu trúc `cond ? value_1 : value_2`.
- Câu điều kiện và vòng lặp.
    - Câu điều kiện: `if-else` và `switch-case`.
    - Vòng lặp: `for`, `while`, `do-while` và `for-each`.
    - Lệnh `break` và `continue`.
    - Phương pháp đánh nhãn (Label).
- Chuỗi và mảng.
    - Tương tác với chuỗi.
    - Tương tác với mảng 1 chiều và 2 chiều.
    - Tham chiếu mảng.
- Xây dựng hàm (phương thức).
    - Định nghĩa hàm.
    - Hàm yêu cầu trả dữ liệu và không trả dữ liệu.
    - Bội số (bộ số/đa tham số) trong hàm.

## 4.2. Hướng đối tượng ([LINK](https://www.notion.so/2-Object-Oriented-Programming-171e3c27ef378101b8e2f70029abf2e0))

- Buổi 13: Ôn tập.
    - Làm bài tập OOP 2.3 trên Notion.
- Buổi 14: Nghiên cứu kiểu mảng động ArrayList.
    - Ôn tập thao tác với mảng tĩnh.
    - Nghiên cứu thao tác với mảng động ArrayList.
- Buổi 15: Ôn tập.
    - Làm bài tập OOP 2.2 trên Notion.
- Buổi 16: Ôn tập.
    - Làm bài tập OOP 2.2 trên Notion (tt).
- Buổi 17: Tính đa hình trong OOP.
    - Tổng quan nội dung.
    - Đối tượng (object) và thể hiện (instance).
    - Ghi đề trong đa hình.
    - Up-casting và Down-casting.
- Buổi 18: Ôn tập.
    - Làm bài tập OOP 2.8 trên Notion.
    - Nghiên cứu về bài toán tìm kiếm và sắp xếp.
- Buổi 19: Tính trừu tượng trong OOP.
    - Bài 2.10: Tính chất trừu tượng trong OOP.
- Buổi 20: Interface trong Java.
    - Bài 2.12: Interface trong Java.

## 4.3. Hệ cơ sở dữ liệu ([LINK](https://local-tip-3d2.notion.site/3-MySQL-171e3c27ef378118ac83f81899b68d53?pvs=74))

## 4.4. Tương tác với hệ cơ sở dữ liệu bằng Java ([LINK](https://local-tip-3d2.notion.site/4-Java-MySQL-171e3c27ef37817495d6f57896aa34e7?pvs=74))

# 5. Bài tập

- Bài tập trên web ([LINK](https://fullhousedev.com/contest/java28)).
- Bài tập mở rộng ([LINK](https://www.notion.so/Exercise-171e3c27ef37812a9754fb9190421d82?pvs=21)).