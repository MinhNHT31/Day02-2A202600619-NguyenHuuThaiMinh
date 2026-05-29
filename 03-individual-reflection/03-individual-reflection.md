# 0.1 — Individual Reflection (Thái Minh — Domain & Synthesis Lead)

## Đóng góp của Thái Minh trong nhóm (Domain & Synthesis Lead)

| Hoạt động | Thái Minh đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Xác định 5 problems từ domain CV/autonomous driving; phân tích từ góc domain expertise và research gap | Nhóm hiểu rõ bối cảnh kỹ thuật và scope các vấn đề từ research perspective |
| Pitch | Pitch Problem #1 (weekly research update) từ góc domain — nhấn mạnh impact trên research velocity và reproducibility | Bài được vào shortlist top-3 vì có domain validation rõ |
| Challenge | Kiểm chứng hypotheses kỹ thuật của nhóm: data format, constraints từ CV pipeline, feasibility của AI intervention | Nhóm loại bớt ideas không feasible từ research perspective; focus vào bài thực hiện được |
| Workflow | Vẽ current/future workflow xem rõ AI intervention points nào phù hợp với research process định kỳ | Nhóm dùng workflow để define AI boundary và human review points |
| Research | Tổng hợp insights từ research domain: pattern trong CV workflows, tools/methods phổ biến trong domain, best practices | Nhóm thấy được standard practices, không reinvent wheel; validate approach với thực tế domain |
| Rule / Workflow / Agent | Phân tích level (Rule/Workflow/Agent) dựa trên domain constraints và research methodology feasibility | Nhóm chọn Workflow vì phù hợp với incremental research validation và có clear human review |

---

## Bảng dùng AI trong reflection — Domain & Synthesis Lead

| Phase | Thái Minh dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Thái Minh sửa gì |
|---|---|---|---|---|
| Scan | Gợi ý problems theo domain CV/autonomous driving; phân tích domain gaps | Giúp nhớ thêm: research velocity issues, experiment tracking, checkpoint management | AI gợi ý vài ý quá rộng hoặc không phù hợp với academic research constraints | Bỏ các ý không có research workflow thật, tập trung vào quy trình thực tế |
| Workflow | Nhờ AI chuyển mô tả research process thành ASCII/Mermaid flow; validate intervention points | Nhanh hơn khi vẽ workflow từ text mô tả; giúp thấy rõ AI boundary | AI gộp nhầm bước dự phòng vào main flow; không hiểu research methodology constraints | Tách rõ fallback, human review points, đảm bảo AI không thay thế research validation |
| Research | Tổng hợp insights: tools/patterns trong CV domain, tool landscape, best practices | Gợi ý references, papers, tools mà domain thường dùng; tiết kiệm thời gian tìm pattern | AI không verify được academic credibility; có gợi ý tools không dùng trong research | Chỉ giữ tools được publish/cited, verify credibility, ghi rõ adoption trong domain |
| Problem Statement | Nhờ AI phản biện field mơ hồ từ domain perspective; validate feasibility | Chỉ ra feasibility risks từ CV/ML perspective, metric có scientific validity hay không | AI đề xuất agent/complex solutions quá sớm; không hiểu research incremental validation | Hạ về Workflow, nhấn mạnh research validation loop, không vội deploy |

---

## Bài học của Thái Minh (Domain & Synthesis Lead)

- Problem tốt không phải problem "AI-friendly" nhất, mà là problem có workflow định kỳ, metric đo được, và feasible từ domain perspective.
- Domain expertise là asset quan trọng khi validate AI intervention points: không phải mọi bottleneck đều cần AI, không phải mọi AI solution đều feasible trong research context.
- Vẽ workflow từ domain perspective giúp nhóm thấy rõ: phần nào là research methodology (cần giữ), phần nào là operational burden (có thể AI hỗ trợ).
- Synthesis từ research domain: AI có thể gợi ý tool/pattern, nhưng Domain Lead phải verify credibility, adoption rate, và scientific validity trước recommend.
- Workflow thích hợp hơn Agent vì: research process là incremental validation, cần human review tại mỗi bước, không thể tự động hóa research decision.
- Scope nhỏ lúc đầu là cách research valid: validate trên 1-2 thực experiments trước khi scale, thay vì build lớn rồi mới discover constraints.

---

## Nếu làm lại (Domain & Synthesis Lead perspective)

Thái Minh sẽ:

1. **Validate domain assumptions sớm hơn** bằng cách hỏi senior researchers: pain point có thật không, baseline metric có đúng không, trước khi chốt target.
2. **Deep-dive vào existing tools/workflows** trong domain trước propose AI intervention, để avoid "not invented here" problem.
3. **Define research validation criteria trước propose solution**: AI draft cần review bởi ai, metric success là gì (scientific validity? efficiency? accuracy?), exit criteria nếu AI không work.
4. **Prototype với real domain data sớm**: không phải tìm tool "perfect" lý thuyết, mà test tools trên real experiments và xem thực tế như thế nào.
5. **Lead team discussion về trade-off**: giữa automation (faster) vs. control (more research rigor) — không phải lúc nào automation cũng tốt cho research.

---

*Individual Reflection — Day 02 Lab v2 (Domain & Synthesis Lead role)*
