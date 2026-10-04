# BÁO CÁO LAB DAY 17: PROBLEM FRAMING & THE MOM TEST INTERVIEW
**Học phần:** Reverse Solution Directive → Problem Hypothesis & Luyện Phỏng Vấn Mom Test  
**Mã kho:** `Track1_Day17_02495_LaiBaQuan`

---

## 1. THÔNG TIN CHUNG
> 📌 *Quy định: Phần này kết hợp thông tin cá nhân của bạn và thông tin chung của nhóm.*

- **Mã học viên (MHV):** 02495 `[CÁ NHÂN]`
- **Họ và tên:** Lại Bá Quân `[CÁ NHÂN]`
- **Tên nhóm:** [Điền tên nhóm của bạn, ví dụ: Nhóm 03] `[THEO NHÓM]`
- **Danh sách thành viên nhóm:** `[THEO NHÓM]`
  1. Lại Bá Quân (02495)
  2. [Họ tên TV 2 - MHV]
  3. [Họ tên TV 3 - MHV]
  4. [Họ tên TV 4 - MHV]
- **Case nghiên cứu đã chọn:** **Case A — AI Tutor: Diagnostic Refresher** `[THEO NHÓM]`

---

## 2. PROBLEM HYPOTHESIS BRIEF (KẾT QUẢ CHẶNG 1)
> 👥 *Quy định: [NỘI DUNG ĐIỀN THEO NHÓM]*  
> *(Toàn bộ thành viên trong nhóm thống nhất nội dung này sau buổi thảo luận Chặng 1)*

### 2.1. Phân Tích Directive & Khả Năng Trung Tính
- **Solution Directive gốc:**
  > *Trigger:* Học viên bấm nút “Tôi vẫn chưa hiểu”.  
  > *Input:* Bài hiện tại, câu trả lời gần đây và lịch sử học tập.  
  > *AI action:* Chẩn đoán và lựa chọn khái niệm nền.  
  > *Output:* Một phần ôn lại ngắn trước khi quay lại bài hiện tại.  
  > *User control:* Học viên chủ động yêu cầu trợ giúp.
- **Capability trung tính (Loại bỏ hoàn toàn UI, AI và tên feature):**
  > Khả năng tự động phát hiện và cung cấp chính xác phần kiến thức nền tảng còn thiếu hụt đang cản trở việc hiểu bài học hiện tại, giúp người học lấp lỗ hổng ngay lập tức mà không phải tự mò mẫm hay rời khỏi ngữ cảnh học tập.

### 2.2. Chuỗi Thay Đổi Kỳ Vọng (Change Chain)
```text
Solution (Chẩn đoán hổng kiến thức nền)
  → Mắt xích 1: Người học nhận ra chính xác khái niệm tiên quyết mà mình đang bị hổng
  → Mắt xích 2: Người học ôn nhanh đúng trọng tâm phần hổng đó trong vài phút thay vì tìm kiếm lan man
  → Outcome: Người học tự tin tiếp tục hoàn thành bài học hiện tại, không bỏ dở giữa chừng
```

### 2.3. Nhóm Đối Tượng Liên Quan (Actors) & Nhánh Lựa Chọn
| Nhóm đối tượng (Actor) | Họ đang làm gì? | Pain / Hậu quả có thể có | Họ hưởng lợi thế nào? |
| :--- | :--- | :--- | :--- |
| **Học viên (Learner)** | Tự học trực tuyến, đọc slide, giải bài lab | Không biết mình hổng chỗ nào, tìm kiếm lan man, dễ nản và bỏ học | Hiểu bài nhanh, không đứt mạch tư duy |
| **Giảng viên / Coach** | Hỗ trợ giải đáp thắc mắc | Bị quá tải bởi những câu hỏi nền tảng lặp đi lặp lại | Tiết kiệm thời gian, tập trung vào ca khó |
| **Người làm nội dung** | Soạn giáo trình, bài tập | Không biết bài giảng bị đứt gãy logic ở khái niệm nào | Có dữ liệu để tối ưu lại giáo trình |

- **Actor nhóm chọn điều tra trước:** **Học viên tự học (Learner)**.
- **Lý do chọn:** Đây là đối tượng trực tiếp trải nghiệm sự bế tắc trong học tập và là người quyết định hành vi tiếp tục học hay bỏ dở.

### 2.4. Tình Huống & Công Việc Cần Hoàn Thành (Situation & JTBD)
- **Tình huống cụ thể:** Khi đang đọc tài liệu hoặc làm bài thực hành mà gặp phải một thuật ngữ, công thức hoặc đoạn logic lạ chưa từng nắm vững.
- **Job-to-be-done (JTBD):** Người học muốn nhanh chóng làm rõ khái niệm bị nghẽn để hoàn thành bài tập kịp tiến độ mà không bị xao nhãng hoặc mất quá nhiều thời gian tra cứu ngoài lề.

### 2.5. Giả Thuyết Nỗi Đau (Pain Hypotheses) & Lựa Chọn
- **Pain Hypothesis A (Giả thuyết chẩn đoán):** Người học *không biết mình đang hổng kiến thức tiên quyết nào*, dẫn đến việc tra cứu sai từ khóa, đọc tài liệu lan man càng làm tăng thêm sự bối rối và tốn thời gian.
- **Pain Hypothesis B (Giả thuyết động lực & sự dài dòng):** Người học biết mình yếu phần nào nhưng *ngại đọc các tài liệu/video giải thích quá dài dòng*, thích giải pháp ăn xổi hoặc đoán mò cho xong việc.
- **Giả thuyết nhóm chọn để điều tra trước:** **Pain Hypothesis A**.
- **Lý do chọn:** Solution directive gốc tập trung vào việc "chẩn đoán khái niệm nền", do đó giả định cốt lõi cần kiểm chứng là người học thực sự gặp khó khăn trong việc tự định vị lỗ hổng kiến thức của mình.

### 2.6. Bản Đồ Bằng Chứng Cần Tìm (Evidence Map)
| Tiêu chí kiểm tra | Bằng chứng làm nhóm tin hơn (Validation) | Bằng chứng làm nhóm nghi ngờ / bác bỏ (Invalidation) |
| :--- | :--- | :--- |
| **Situation có thật** | User kể lại được tình huống cụ thể trong 7 ngày qua bị tắc ở 1 bài học xác định. | User nói học bài nào cũng hiểu, hoặc lâu rồi không tự học bài mới nào. |
| **Pain có ý nghĩa** | User mất trên 30 phút tự xoay xở nhưng vẫn không hiểu; cảm thấy bất lực, bực bội. | User thấy việc không hiểu là bình thường, chỉ cần lướt qua hoặc xem đáp án là xong. |
| **Workaround tồn tại** | User đã mở Google search thử 3-4 từ khóa, hỏi bạn bè, mở ChatGPT giải thích lại. | User không làm gì cả, lập tức bỏ qua câu hỏi đó mà không tìm cách xử lý. |
| **Consequence có thật** | Trễ deadline bài tập, bỏ dở khóa học, bị điểm kém bài kiểm tra. | Không có hậu quả nào đáng kể, bài tập vẫn nộp đúng hạn và đạt điểm tốt. |
| **Pattern lặp lại** | Tình trạng này xảy ra định kỳ mỗi khi bước sang module hoặc chủ đề mới. | Chỉ là sự cố hy hữu một lần do đề bài bị lỗi chính tả/lỗi link. |

### 2.7. Solution Parking Lot (Ít nhất 5 hướng giải pháp, có hướng Non-AI)
| STT | Hướng giải quyết đề xuất | Loại giải pháp (AI / Non-AI) |
| :---: | :--- | :---: |
| 1 | AI Diagnostic Micro-Refresher (theo directive gốc) | **AI** |
| 2 | Trợ lý ảo gợi mở tư duy theo phương pháp Socratic thay vì đưa đáp án | **AI** |
| 3 | **Prerequisite Knowledge Map:** Bảng danh mục các khái niệm nền tảng cần biết kèm link ôn nhanh đặt ở đầu mỗi bài học | **Non-AI** |
| 4 | **Interactive Glossary Tooltip:** Di chuột vào thuật ngữ khó sẽ hiển thị tóm tắt 2 câu định nghĩa cơ bản | **Non-AI** |
| 5 | **Cộng đồng hỏi đáp ngang hàng (Peer Help Desk):** Nút gắn cờ báo "Cần bạn học giải thích lại đoạn này" | **Non-AI** |

---

## 3. CONVERSATION GUIDE PHIÊN BẢN CUỐI CÙNG
> 👥 *Quy định: [NỘI DUNG ĐIỀN THEO NHÓM - ĐÃ CẬP NHẬT SAU CHẶNG 4]*  
> *(Đây là bản kịch bản phỏng vấn đã được nhóm tinh chỉnh, loại bỏ câu hỏi dẫn dắt sau khi thực hành phỏng vấn ở Chặng 3)*

### 3.1. Tiêu Chí Tuyển Người & Sàng Lọc (Recruitment Screener)
- **Tiêu chí:** Người học có tham gia các buổi học/tự học trực tuyến trong vòng 7 ngày qua và có ít nhất 1 lần gặp khó khăn trong việc hiểu nội dung bài học.
- **Câu hỏi xác nhận (Recruitment Check):**  
  > *"Trong 7 ngày vừa qua, bạn có buổi học hoặc bài thực hành nào mà bạn đọc tài liệu hoặc nghe giảng nhưng cảm thấy bị nghẽn/chưa hiểu rõ một đoạn kiến thức không?"*

### 3.2. Lời Mở Đầu (Intro & Consent)
> *"Chào bạn, mình đang thực hiện một bài tập nghiên cứu về trải nghiệm tự học và những trở ngại thường gặp khi tiếp cận kiến thức mới của học viên. Buổi nói chuyện này hoàn toàn nhằm mục đích học tập cá nhân, không đánh giá bất kỳ sản phẩm hay dịch vụ nào. Để tiện ghi chép và không bỏ sót thông tin, mình xin phép được ghi âm lại cuộc trò chuyện này nhé?"*

### 3.3. Câu Hỏi Mở Đầu Tình Huống (Story Opener)
> *"Bạn có thể nhớ lại và chia sẻ về lần gần đây nhất khi bạn đang tự học một bài học mà gặp một phần kiến thức hoặc đoạn logic rất khó hiểu không? Lúc đó bạn đang học môn gì, ở đâu và cụ thể bối cảnh thế nào?"*

### 3.4. Bộ Ba Câu Hỏi Trọng Tâm (Big 3 Questions)
1. **Hỏi về Hành Vi & Phản Xạ:**  
   > *"Ngay khi phát hiện mình không hiểu đoạn đó, chính xác bạn đã làm những gì đầu tiên để xử lý?"*
2. **Hỏi về Rào Cản & Workaround Thực Tế:**  
   > *"Khi bạn tìm cách tự giải quyết (như tra cứu/hỏi han), bạn đã gặp khó khăn hay điểm nghẽn gì lớn nhất? Bạn đã mất khoảng bao nhiêu thời gian cho việc đó?"*
3. **Hỏi về Hậu Quả Cụ Thể (Câu hỏi kiểm tra độ nặng của Pain):**  
   > *"Sau khi thử các cách đó, kết quả cụ thể thế nào? Bạn có hiểu được bài để làm tiếp không, hay sự việc đó dẫn đến hậu quả gì cho việc học của bạn?"*

### 3.5. Ngân Hàng Câu Hỏi Đào Sâu (Probe Bank)
- *"Lúc đó chuyện gì xảy ra tiếp theo?"*
- *"Cụ thể là bạn đã gõ từ khóa gì để tìm?"*
- *"Vì sao bạn lại chọn cách đó thay vì hỏi mentor hay bạn cùng lớp?"*
- *"Phần nào trong quá trình tự tìm hiểu làm bạn thấy mất công nhất?"*
- *"Bạn đã thử cách nào khác nữa chưa?"*

### 3.6. Cơ Chế Phản Xạ The Mom Test Khi Bị Lệch Dữ Liệu
- **Khi user khen giải pháp:** 👉 **Deflect:** *"Cảm ơn bạn, nhưng quay lại trải nghiệm tuần trước, khi không có ai hỗ trợ thì bạn đã tự xử lý thế nào?"*
- **Khi user nói chung chung / hứa tương lai:** 👉 **Anchor:** *"Đó là thường thì, còn ở sự việc cụ thể hôm thứ Ba mà bạn vừa nhắc, bạn đã làm gì?"*
- **Khi user đòi hỏi tính năng / giải pháp:** 👉 **Dig:** *"Điều đó sẽ giúp bạn giải quyết được vướng mắc cụ thể nào mà cách làm hiện tại chưa làm được?"*

---

## 4. PRACTICE REFLECTION (CÁ NHÂN)
> 👤 *Quy định: [NỘI DUNG ĐIỀN CÁ NHÂN - LẠI BÁ QUÂN]*  
> *(Dựa trên chính lượt phỏng vấn thực tế của bạn với học viên ngoài nhóm ở Chặng 3)*

### Câu 1: Câu hỏi nào trong buổi phỏng vấn đã giúp user kể được một tình huống cụ thể nhất?
- *Trả lời:* [Điền câu hỏi thực tế bạn đã hỏi và phản ứng của interviewee, ví dụ: "Câu hỏi 'Lúc đó bạn gõ từ khóa gì lên Google?' đã giúp user nhớ lại việc họ tìm từ khóa X nhưng ra toàn tài liệu chuyên sâu không hiểu gì..."]

### Câu 2: Chỗ nào bản thân bạn nhận thấy cần phải làm tốt hơn ở lần phỏng vấn thật tiếp theo?
- *Trả lời:* [Điền điểm yếu bạn đã mắc phải, ví dụ: "Mình vẫn còn xu hướng nói hơi nhiều và lỡ ngắt lời khi bạn ấy đang suy nghĩ; có lúc suýt hỏi 'Bạn có muốn có bài tóm tắt ngắn không'..."]

### Câu 3: Sau khi cả nhóm cùng luyện, nhóm đã quyết định sửa đổi Conversation Guide ở những điểm nào và vì sao?
- *Trả lời:* [Điền lý do nhóm sửa guide, ví dụ: "Nhóm đã bỏ câu hỏi 'Bạn thường làm gì khi không hiểu' vì câu này khiến user trả lời lý thuyết; nhóm thay bằng câu hỏi trực diện 'Lần gần nhất bạn học bài gì và tắc ở đâu'..."]

---

## 5. BÁO CÁO SỬ DỤNG AI (AI SUPPORT LOG)
> 📌 *Quy định: [NỘI DUNG ĐIỀN CÁ NHÂN]*  
> *(Khai báo minh bạch theo đúng quy định liêm chính học thuật của bài lab)*

### 5.1. Những việc AI đã hỗ trợ:
- Gợi ý cách diễn đạt trung tính cho Capability từ Solution Directive của Case A.
- Đóng vai trò phản biện (Reviewer) để rà soát các câu hỏi vi phạm quy tắc The Mom Test (phát hiện câu hỏi dẫn dắt, câu hỏi hướng về tương lai).
- Hỗ trợ xây dựng cấu trúc template báo cáo chuẩn chỉnh theo yêu cầu của bài lab.

### 5.2. Điểm hạn chế / hời hợt / sai lệch của AI:
- Ban đầu, AI vẫn gợi ý một số câu hỏi khảo sát mang tính đánh giá ý kiến như: *"Bạn có muốn một công cụ ôn tập ngắn gọn không?"* hoặc *"Theo bạn tính năng AI nào sẽ giúp bạn học tốt hơn?"*. Đây là những câu hỏi vi phạm hoàn toàn nguyên tắc The Mom Test.
- AI có xu hướng mặc định rằng "người học luôn luôn khao khát được ôn lại kiến thức nền", trong khi thực tế người học có thể chỉ muốn giải nhanh bài tập để đối phó deadline.

### 5.3. Người học đã tự hiệu chỉnh và hoàn thiện như thế nào:
- Tự tay loại bỏ toàn bộ các câu hỏi giả định hoặc hỏi về giải pháp mà AI gợi ý.
- Chuyển hướng 100% câu hỏi về các sự kiện và hành vi đã diễn ra trong quá khứ 7 ngày gần nhất.
- Trực tiếp tiến hành phỏng vấn người thật, tự nghe lại bản ghi âm và tự rút ra phản xạ cá nhân chứ không dùng AI để tạo dữ liệu giả lập.
