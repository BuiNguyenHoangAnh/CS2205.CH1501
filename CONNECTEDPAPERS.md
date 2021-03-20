# QT18: SỬ DỤNG CONNECTEDPAPERS

[ConnectedPapers](https://www.connectedpapers.com) là một website hỗ trợ khám phá những paper liên kết với nhau như thế nào dưới dạng đồ thị (graph)

Thông qua sử dụng ConnectedPapers, chúng ta có thể:
- Có một cái nhìn toàn cảnh về một lĩnh vực nghiên cứu (mới) .
- Chắc chắn rằng mình không bỏ lỡ một paper quan trọng nào.
- Tạo bibliography để hỗ trợ trích dẫn. 
- ...


### Cách sử dụng: 

1) Tìm kiếm một paper: 
Người dùng có thể tìm kiếm thông tin 1 paper dựa trên các yếu tố: 
  + Tên paper 
  + Mã DOI
  + Link arXiv
  + Link Semantic Scholar 
  + Link PubMed

![image](https://user-images.githubusercontent.com/25763738/111873683-1262eb00-89c4-11eb-9864-ad7cf55f9802.png)

Điền thông tin vào ô tìm kiếm, sau đó chọn Build a graph. Sau đó giao diện 1 graph hiện ra: 

![image](https://user-images.githubusercontent.com/25763738/111873726-56ee8680-89c4-11eb-9cc3-ae5f9f86fd5e.png)


1 Graph sẽ bao gồm 1 mạng lưới liên kết khá dày đặc của các papers với nhau (dựa trên trích dẫn từ paper gốc và các paper liên quan).
Một số thông tin được hiển thị bao gồm: 
  + Paper liên quan 
  + Thông tin chi tiết (tác giả, hội nghị, năm, ...) + phần Abstract của paper. 
  + Prior works: sắp xếp các trích dẫn từ các paper trên, từ đó ta xác định nội dung trọng tâm cần nghiên cứu đạt được nếu tiến hành nghiên cứu. 
  (Vd: Paper *Incorporating BERT into Neural Machine Translation* -> Build a Graph, sau đó dựa vào graph, hệ thống Prior works sẽ gợi ý ta nghiên cứu trước hết là Paper Attention is all you Need -> BERT... -> Neural Machine Translation ...
  ![image](https://user-images.githubusercontent.com/25763738/111873869-13e0e300-89c5-11eb-9f8e-ce0cda38527c.png)
  
  + Derivative works: sắp xếp các paper khác đã trích dẫn những paper liên quan trong graph hiện tại. Qua đó chúng ta có thể biết được tầm ảnh hưởng của paper ta đang quan tâm. 
  (Vd: Paper tốt, chất lượng sẽ được trích dẫn nhiều. Hay biết được topic/hướng tiếp cận của paper đó có được quan tâm trong những năm gần dây hay không)
  ![image](https://user-images.githubusercontent.com/25763738/111873993-aa150900-89c5-11eb-9dd2-bd5a8fe6faa4.png)
  
  ==========
  Thanks for viewing, here is a meme.
  
  ![image](https://user-images.githubusercontent.com/25763738/111874036-e47ea600-89c5-11eb-8d8d-d62438dca039.png)


  
