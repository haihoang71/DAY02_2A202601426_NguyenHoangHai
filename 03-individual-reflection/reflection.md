# 03 — Individual Reflection 

## Đóng góp trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra 8 problems (3 top candidates về quản lý tài nguyên, sức khỏe và viết báo cáo) | Nhóm có nguồn candidate đa dạng, thực tế để đưa vào bể gom chung |
| Điều phối & Chốt quyết định | Chủ trì thảo luận Phase 3, 4, 5, 6; điều phối đánh giá tiêu chí và chốt quyết định "Not Yet" | Nhóm đồng thuận chọn Candidate 3 (Tập sai form ở gym), giữ nguyên kỷ luật đánh giá dựa trên evidence |
| Challenge & Phản biện | Đặt câu hỏi về tính khả thi của RAG/Vector DB (Candidate 1) và evidence cho Candidate 2 | Nhóm tránh được cái bẫy chọn giải pháp quá nặng cho buổi lab hoặc chọn problem thiếu evidence |
| Quy trình & Boundary | Cùng nhóm xác định boundary/fallback cho AI (chuyển sang PT thật khi có bất thường) | Thiết lập được điểm chặn an toàn, tránh để AI đưa ra quyết định quá thẩm quyền |
| Phân tích giải pháp | Định hướng chọn mức Workflow thay vì Agent ở giai đoạn pilot | Bài toán được thu hẹp scope đúng sức, có lộ trình mở rộng thực tế |

---

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Gợi ý scan các problem từ góc độ cá nhân (công việc, sức khỏe, thói quen) | Gợi ý được cấu trúc problem rõ ràng (Problem, Actor, Bottleneck, Impact) | Đưa ra một số ý thuần túy kỹ thuật chuyên sâu khi chưa có yêu cầu | Điều chỉnh lăng kính sang các pain point đa dạng hơn (sức khỏe, tổ chức cá nhân) |
| Problem Cards | Chuẩn hóa thông tin top 3 problem card theo mẫu | Điền đầy đủ cấu trúc các trường thông tin nhanh chóng | Gợi ý Quick gut lên mức Agent quá sớm cho các bài toán đơn giản | Hạ Quick gut về mức Rule / Workflow phù hợp với scope |
| Workflow | Tạo mã Mermaid vẽ sơ đồ Before/After cho 3 problem | Tạo khung sơ đồ Mermaid chính xác syntax, tiết kiệm thời gian vẽ | Các bước trong sơ đồ ban đầu còn hơi gộp, chưa làm nổi bật điểm nghẽn | Tách rõ các bước bottleneck (như đoạn đứt gãy do ngại hỏi/chờ lịch) |
| Convergence & Decision | Phản biện các tiêu chí chấm điểm candidate | Gợi ý bộ khung 7 tiêu chí chấm điểm đa chiều | AI đề xuất chọn luôn Agent và cấp phép Go ngay khi thiếu data | Cùng nhóm chốt quyết định "Not Yet", giữ mức Workflow và đặt điều kiện validate thực tế |

---

## Bài học cá nhân

- **Problem tốt cần evidence thật:** Một vấn đề đau thật với bản thân chưa chắc đã là một problem tốt cho nhóm nếu thiếu evidence thị trường hoặc baseline khách quan để đo lường.
- **Vai trò Trưởng nhóm là giữ kỷ luật tiêu chí:** Khi thảo luận, nhóm dễ bị cuốn theo các giải pháp "kỹ thuật hay" (như RAG/Vector DB hay Agent). Người điều phối phải giữ nhóm bám sát tiêu chí: *Làm được trong lab không? Evidence có đủ mạnh không?*
- **Agent không phải câu trả lời duy nhất:** Ma trận độ phức tạp/mơ hồ cho thấy Agent có thể phù hợp, nhưng Workflow mới là lựa chọn tối ưu cho giai đoạn pilot vì kiểm soát được rủi ro và dễ triển khai.
- **Quyết định "Not Yet" là một quyết định đúng đắn:** Nhìn nhận rõ các khoảng trống (data thị trường VN, độ chính xác camera đơn, người thật review) giúp nhóm tránh việc cam kết số liệu ảo hoặc cố Go khi chưa đủ điều kiện.

Nếu làm lại:

```text
Tôi sẽ chủ động tổ chức phỏng vấn nhanh (Option A) ngay tại chỗ với 2–3 bạn trong lớp có tập gym 
để xác nhận pain point tại Việt Nam, thay vì hoàn toàn phụ thuộc vào dữ liệu thứ cấp từ thị trường Mỹ.