# Day 02 Lab - Tìm đúng bài toán cho AI

Thông tin bài nộp:

- Mã học viên: `2A202600619`
- Họ tên: `Nguyễn Hữu Thái Minh`
- Hướng bài làm: `Researcher / computer vision / autonomous driving`
- Case nhóm chọn: `Tự động hóa báo cáo tiến độ định kỳ từ hoạt động đã làm`

## Cấu trúc bài nộp

| Phần | File |
|---|---|
| 01 - Individual Problem Scan | [01-individual-problem-scan.md](01-individual-problem-scan/01-individual-problem-scan.md) |
| 02 - Group Problem Statement | [02-group-problem-statement.md](02-group-problem-statement/02-group-problem-statement.md) |
| 02 - Future Workflow Diagram | [future_workflow_v1.svg](02-group-problem-statement/future_workflow_v1.svg) |
| 03 - Individual Reflection | [03-individual-reflection.md](03-individual-reflection/03-individual-reflection.md) |

## Tóm tắt bài làm

Phần 01 scan 5 problems từ trải nghiệm researcher CV/autonomous driving, sau đó chọn top 3 để phát triển Problem Cards. Ba vấn đề nổi bật nhất là:

1. Weekly research update: tổng hợp experiment, metric, survey method và chốt hướng demo hằng tuần.
2. Tìm lại quyết định nghiên cứu / triển khai cũ bị phân tán trong chat, docs, notebook.
3. Viết weekly progress note hoặc meeting summary rõ ràng, đủ action items và context.

Phần 02 hội tụ nhóm về bài toán báo cáo tiến độ định kỳ vì có workflow rõ, metric thời gian đo được, và có thể so sánh Rule / Workflow / Agent một cách minh bạch. Nhóm đi từ candidate chung đến validation nhanh, research giải pháp có sẵn, rồi chốt mức chọn là Workflow.

Phần 03 ghi lại đóng góp cá nhân của Thái Minh với vai trò Domain & Synthesis Lead: xác định vấn đề theo domain, challenge feasibility, tổng hợp research patterns, và giữ AI intervention ở mức có human review rõ ràng.

## Quyết định cuối

Mức chọn: `Workflow`.

Decision: `Go với scope nhỏ`.

Lý do: Bài toán có workflow rõ, AI chỉ hỗ trợ một đoạn cụ thể sau khi gom note/commit/milestone, còn researcher/sinh viên vẫn review và tự gửi. Cách này giữ được kiểm soát chất lượng, tránh overbuild agent, và dễ pilot bằng dữ liệu thật trước khi mở rộng.
