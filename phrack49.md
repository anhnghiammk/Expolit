###I. Cấu trúc bộ nhớ 
  Để hiểu những gì bộ đệm của stack đầu tiên chúng ta phải hiểu quá trinh này được tổ chức như thế nào trong bộ nhớ. Quá trình được chia làm 3 phần. Text, Data và Stack. Chúng ta sẽ tập trung về phần Stack, nhưng trước tiên cần có một cái nhìn tổng quan các khu vực nhỏ khác theo thứ tự.
  
  Các khu vực văn bản được cố định bởi chương trình và bao gồm cả code, chỉ đọc dữ liệu. Khu vực này tương ứng với phần văn bản của các tệp tin được thực thi. Khu vực này được đánh dấu chỉ đọc và bất kỳ sự xâm phạm để ghi nó sẽ dẫn đến kết quả trong một segmentation violation.

  Khu vực chứa data được khởi tạo và chưa được khởi tạo. Các biến tĩnh được lưu trữ ở khu vực này. 
