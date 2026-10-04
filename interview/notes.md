# Interview Record — Case B: AI Notes

## Thông tin buổi phỏng vấn

- **Ngày phỏng vấn:** 4/10/2026
- **Interviewer:** Nguyễn Thị Hồng Nhung
- **Mã người tham gia:** 2A202602797
- **Hình thức:** Trực tiếp
- **Độ dài:** 2 phút 49 giây
- **Recruitment check:** Có nội dung phù hợp; người tham gia cho biết gần đây đã học Cloud buổi 12 và muốn nhớ/xem lại một số ý. Thời điểm chính xác chưa rõ.
- **Đồng ý ghi âm:** Có — người tham gia đồng ý cho ghi âm để phục vụ bài tập.
- **Tệp ghi âm hoặc link (nếu có):** D:\AI THUC CHIEN\Track1_Day17_MHV_HoVaTen\interview\recording.mp3

## Câu chuyện gần nhất

- **Bài học/nội dung và thời điểm:** Gần đây, trong buổi học Cloud buổi 12, người tham gia đọc slide “Agent không phải Web App bình thường”. Ngày học cụ thể chưa được nêu.
- **Bối cảnh:** Người tham gia đang đọc slide về những điểm cần lưu ý khi triển khai AI Agent. Địa điểm và các điều kiện học khác chưa được nêu.
- **Mục tiêu lúc đó:** Hiểu và nhớ ba đặc điểm của Agent: chạy lâu (long-running), có trạng thái/lịch sử hội thoại (stateful), và có thể tốn nhiều token/chi phí (costly); muốn xem lại cách các đặc điểm này ảnh hưởng đến triển khai.
- **Điều khiến nội dung đáng chú ý hoặc khó:** Người tham gia mô tả nội dung là mới, nhiều khái niệm và cô đọng; ban đầu chưa liên kết được ba đặc điểm với các thách thức triển khai thực tế.

## Diễn biến và hành vi thực tế

| Trình tự                              | Điều đã xảy ra / người tham gia đã làm                                                             | Chi tiết hoặc trích dẫn gần nguyên văn                                                                                     |
| ------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Trong lúc học                         | Đọc slide một lượt để nắm ý chung, sau đó đọc lại các phần Long-running, Stateful và Costly.       | “Ban đầu, mình đọc slide một lượt để nắm ý chung. Sau đó mình đọc lại từng phần...”                                        |
| Khi nhận ra điểm quan trọng/chưa hiểu | Tập trung vào ba đặc điểm và thử tự diễn đạt chúng theo cách dễ hiểu hơn.                          | Nêu ví dụ Agent chạy lâu có thể gặp giới hạn thời gian của gateway/proxy; gửi lại lịch sử hội thoại có thể làm tăng token. |
| Sau buổi học                          | Có một vài ý muốn giữ lại để xem lại; ghi lại điểm chưa rõ để hỏi thêm hoặc xem tài liệu sau.      | “Những chỗ chưa rõ, mình ghi lại để có thể hỏi thêm hoặc xem lại tài liệu sau.”                                            |
| Kết quả tiếp theo                     | Nắm được thông điệp chính nhưng cần thêm thời gian để liên kết các đặc điểm với vấn đề triển khai. | “Mình hiểu được thông điệp chính... Tuy nhiên, mình chưa hiểu hết ngay từ đầu.”                                            |

## Khó khăn, workaround và hậu quả

- **Khó khăn/barrier được kể:** Nhiều khái niệm mới được trình bày cô đọng và có liên hệ với nhau. Người tham gia chưa hiểu ngay vì sao việc Agent chạy lâu, duy trì trạng thái/lịch sử hội thoại và sử dụng nhiều token lại tạo thách thức triển khai.
- **Cách họ tự xử lý/workaround:** Đọc slide lại; tách nội dung thành ba ý; tự diễn đạt lại bằng lời của mình; ghi lại điểm chưa rõ để xem tài liệu hoặc hỏi thêm sau.
- **Công sức/chi phí:** Đã phải đọc lại và dành thêm thời gian để hiểu/liên kết các ý. Thời lượng và số lần đọc cụ thể chưa được nêu.
- **Hậu quả thực tế:** Hiểu được thông điệp chung nhưng chưa hiểu hết ngay; cần thêm thời gian và còn một số ý muốn xem lại. Không có hậu quả nào khác được kể.
- **Tần suất/lần gần nhất trước đó:** Chưa được hỏi/chưa có thông tin.
- **Họ có quay lại xem hoặc xử lý nội dung không?** Chưa xác nhận đã quay lại sau buổi học. Người tham gia nói đã đọc lại slide trong lúc học và ghi lại điểm chưa rõ để xem lại sau.

## Trích dẫn và tín hiệu đáng chú ý

- **Exact quote 1:** “Khó nhất là slide trình bày nhiều khái niệm mới trong một khoảng ngắn, trong khi các ý có liên quan với nhau.” — Mô tả khó khăn khi đọc slide.
- **Exact quote 2:** “Mình chia nội dung thành ba ý riêng, đọc lại từng phần và tự diễn đạt bằng lời của mình để kiểm tra xem đã hiểu chưa.” — Cách người tham gia tự xử lý.
- **Điều bất ngờ hoặc mâu thuẫn với giả thuyết:** Người tham gia đã chủ động đọc lại và ghi chú điểm chưa rõ; điều này cho thấy có workaround cá nhân. Chưa có đủ thông tin để biết cách này có hiệu quả lâu dài hay có pain lặp lại.
- **Điều chưa rõ cần hỏi tiếp:** Khi nào chính xác diễn ra buổi học? Người tham gia có quay lại xem ghi chú/slide sau đó không, và nếu có thì đã làm gì? Tình huống tương tự xảy ra bao lâu một lần, mất bao nhiêu thời gian và có ảnh hưởng đến việc học hay không?

## Evidence và nhận định sau phỏng vấn

| Giả thuyết cần kiểm tra                      | Evidence ủng hộ                                                                                                  | Evidence làm giả thuyết yếu đi / chưa đủ                                                                                                   |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Pain A — khó ghi nhận trong lúc học          | Người tham gia nói nội dung mới, nhiều khái niệm và cần đọc lại; đã tách ý, tự diễn đạt và ghi lại điểm chưa rõ. | Chưa kể rằng mình bỏ sót hoặc không thể ghi nhận điểm quan trọng/chưa hiểu trong lúc học. Chưa có bằng chứng về hậu quả của việc ghi nhận. |
| Pain B — ghi nhận nhưng không quay lại xử lý | Người tham gia có ghi lại điểm chưa rõ để xem lại hoặc hỏi thêm sau.                                             | Chưa xác nhận họ có thực sự quay lại xử lý hay không; chưa kể có quên, trì hoãn hoặc gặp trở ngại sau buổi học.                            |

- **Workaround đã được xác nhận:** Đọc lại slide; chia nội dung thành ba ý; diễn đạt lại bằng lời của mình; ghi lại điều chưa rõ để xem tài liệu hoặc hỏi thêm.
- **Consequence đã được xác nhận:** Cần đọc lại và dành thêm thời gian; ban đầu chưa hiểu hết và còn ý muốn xem lại. Chưa có bằng chứng về tác động lớn hơn đến kết quả học tập.
- **Pain có vẻ đáng kể đến mức nào, dựa trên evidence nào?** Có một khó khăn cụ thể khi hiểu nội dung cô đọng và liên kết các khái niệm, nhưng mức độ đáng kể chưa rõ. Người tham gia có workaround và đã nắm được ý chính; chưa có dữ liệu về tần suất, thời gian cụ thể hoặc hậu quả kéo dài.
- **Cập nhật giả thuyết:** Chưa đủ evidence để kết luận. Câu chuyện gợi ý có khó khăn trong việc xử lý/ghi nhớ nội dung mới, nhưng chưa xác nhận rõ Pain A (khó ghi nhận) hoặc Pain B (không quay lại xử lý).
- **Câu hỏi cần kiểm chứng ở cuộc phỏng vấn tiếp theo:** Sau buổi học, bạn có mở lại slide hoặc ghi chú không? Hãy kể lần gần nhất bạn làm vậy. Có phần nào bị quên hoặc phải tìm lại không? Việc đọc lại/tự ghi chú mất bao lâu và tình huống tương tự thường xảy ra như thế nào?
