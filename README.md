# NNR
NVT Nonstandard Reasoner for OWL ontologies

Các bước thực hiện để chạy chương trình thử nghiệm:
1) Tải các files về máy tính của bạn.
2) Đặt các ontology thử nghiệm trong thư mục ontologies. Cấu trúc thư mục là như sau:

NNR
    ontologies
        mad_cows_incoherent2.owl
        miniEconomy_incoherent.owl
        your_incoherent_ontology.owl
    NNR.jar
    run.bat
    README.md
    
3) Tại cửa sổ lệnh, chạy chương trình thực nghiệm như ví dụ sau
a) Trường hợp 1
C:\path\to\NNR>run NNR.jar your_incoherent_ontology.owl SEM uc_sub_c 0

Ý nghĩa:
- your_incoherent_ontology.owl là tên tệp ontology muốn thí nghiệm. Tệp này được đặt trong thư mục ontologies.
- SEM: thử nghiệm với hàm chọn dựa trên độ liên quan ngữ nghĩa.
- uc_sub_c: thử nghiệm với các truy vấn được thành lập uc \sub c? trong đó uc là khái niệm không thoả được trong ontology đầu vào, c là các khái niệm còn lại trong ontology đầu vào.

