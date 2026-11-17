### Bước 1: Phân tích lỗi
Dựa vào prompt cũ (*"Hãy giải thích ngắn gọn các nội dung của Chain-of-Thought, Prompt Chaining, xử lý đứt gãy"*), AI thường có xu hướng sinh ra văn bản dài dòng. Dưới đây là 3 phần văn bản thừa thãi thường gặp cần loại bỏ:
1. **Lời chào hỏi / Dạ vâng ở đầu câu**
2. **Đoạn dẫn nhập / Giải thích râu ria**
3. **Lời kết luận / Xã giao ở cuối**

---

### Bước 2: Viết prompt tối ưu
**Prompt mới:**
> Giải thích ngắn gọn các khái niệm: Chain-of-Thought, Prompt Chaining, và xử lý đứt gãy ngữ cảnh. 
> **Yêu cầu bắt buộc:** 
> - Trình bày bằng gạch đầu dòng (bullet points).
> - Trả lời trực tiếp vào trọng tâm, tuyệt đối không có lời chào hỏi ở đầu, không có đoạn dẫn nhập và không có lời kết luận ở cuối.

---

### Kết quả phản hồi của AI (Để nộp kèm theo bài)
- **Chain-of-Thought (CoT):** Kỹ thuật yêu cầu AI suy luận chi tiết "từng bước một" trước khi đưa ra kết quả cuối cùng, giúp giải quyết các bài toán logic hoặc phức tạp với độ chính xác cao hơn.
- **Prompt Chaining:** Kỹ thuật chia nhỏ một nhiệm vụ lớn và phức tạp thành một chuỗi các prompt nhỏ liên tiếp nhau, trong đó đầu ra của prompt trước được dùng làm đầu vào cho prompt sau.
- **Xử lý đứt gãy ngữ cảnh:** Kỹ thuật duy trì tính nhất quán trong các hội thoại dài (ví dụ: dùng lệnh "continue generating" hoặc tóm tắt lại bối cảnh) để tránh việc AI quên thông tin hoặc đi lạc đề do vượt quá giới hạn bộ nhớ (token limit).
