# 0.1 — Individual Problem Scan (researcher — computer vision / autonomous driving)

Phiên bản này làm theo hướng dẫn trong `02-deliverable-example.md`: scan rộng, top-3 shortlist, và Problem Cards chi tiết (kèm current/future workflow ASCII). Bạn đã yêu cầu giữ 5 problems; tôi đã chọn top-3 (1–3) để phát triển Problem Cards.

## Scan (5 problems)

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Tốn thời gian / Lặp lại | Weekly research update: tổng hợp kết quả experiment, metric, plan; survey methods; chốt top-3 phương pháp demo | Researcher, PI, Mentor | Mất nhiều giờ/tuần, update hay trễ, mentor hỏi lại chi tiết |
| 2 | Tìm kiếm / Context | Tìm lại quyết định nghiên cứu/triển khai cũ bị phân tán trong chat/docs | Researcher, implementer | 10–30 phút/lần tìm, có hành động sai do thiếu context |
| 3 | Biên tập / Communication | Viết weekly progress note hoặc meeting summary rõ ràng, gắn action items | Researcher, team, mentor | Notes rời rạc, nhiều action item bị quên, feedback yêu cầu giải thích thêm |
| 4 | Research prioritization | So sánh nhiều phương pháp/paper để chọn candidate cho prototyping | Researcher, team | Danh sách dài, thiếu tiêu chí đo, khó chọn 3 phương án demo |
| 5 | Demo readiness | Chuẩn bị demo/checkpoint: tóm tắt goal, data, metric, results, known issues | Researcher, mentor | Demo thiếu chuẩn bị, mentor không nắm được scope trong 1–2 phút |

---

## Top 3 (shortlist)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Weekly research update | Workflow định kỳ, có metric và artefacts để đo; impact cao lên tiến độ nghiên cứu | Cần chuẩn hoá inputs giữa experiments khác nhau |
| 2 | Tìm lại quyết định cũ | Gây delay và lỗi triển khai nếu không có provenance | Data source phân tán (chat, PR, notebook) khó truy xuất tự động |
| 3 | Viết weekly progress note | Ảnh hưởng tới truyền thông nhóm và quyết định mentor; có thể cải thiện bằng workflow + AI | Mức độ technical detail cần giữ tùy case; phải tránh AI viết thay researcher |

---

## Problem Card #1 — Weekly research update

**Problem (tóm tắt):** Researcher mất nhiều thời gian mỗi tuần để gom kết quả experiment, làm rõ problem & metric, survey phương pháp và chốt top-3 phương án demo.

**Actor:** Researcher (autonomous driving CV) và mentor/PI.

**Thời điểm / Bối cảnh:** Hàng tuần, chuẩn bị weekly report cho nhóm nghiên cứu và mentor.

**Current workflow:**

1. Thu thập kết quả experiment & logs
2. Ghi note thô về observations
3. Tự survey nhanh paper/repos liên quan
4. Viết draft update (kết quả, metric, next steps)
5. Gửi cho mentor, nhận feedback

**Bottleneck:** Viết draft và survey candidate methods — mất nhiều thời gian (2–4 giờ/tuần), dễ bỏ sót context.

**Impact:** Trễ update, mentor không kịp give direction, chậm chọn hướng demo.

**Success metric:** Rút thời gian chuẩn bị weekly update xuống <60 phút; top-3 methods có đủ artifact để demo trong 1 tuần.

**Non-AI alternative:** Template báo cáo + checklist experiment; assignment rõ ràng cho từng experiment.

**AI hypothesis:** AI hỗ trợ tổng hợp logs → tóm tắt insight → survey nhanh candidate methods và draft update; researcher review trước khi gửi.

**Quick gut:** Workflow (AI hỗ trợ bước ngôn ngữ/tóm tắt).

### Draft current workflow (ASCII)

```text
CURRENT STATE — ~2-4h/week

[Collect results & logs]
    ↓
[Raw notes / observations]
    ↓
[Manual quick survey of papers/repos]
    ↓
[Draft update: results, metric, plan]
    ↓
[Mentor review]

Bottleneck: Manual survey + Draft update
```

### Draft future workflow (ASCII)

```text
FUTURE STATE — ~30-60min/week

[Collect results & logs] --(script)--> [structured input]
    ↓
[AI synthesize + survey candidate methods] --> [ranked shortlist]
    ↓
[Researcher review & pick top-3]    <-- human boundary
    ↓
[AI draft update (structured)]
    ↓
[Researcher finalize & send]

Fallback: AI draft không đạt -> researcher viết tay
```

---

## Problem Card #2 — Tìm lại quyết định nghiên cứu

**Problem (tóm tắt):** Quyết định/điểm thiết kế phân tán trong chat/docs, mất thời gian truy xuất provenance.

**Actor:** Researcher / Implementer.

**Current workflow (ASCII):**

```text
[Need decision/question]
    ↓
[Search chat / PR / notebook]  -- manual --> open threads
    ↓
[Read context & confirm]
    ↓
[Document provenance / action]
```

**Bottleneck:** Tài liệu và trao đổi phân tán; thiếu link rõ provenance.

**Success metric:** Rút thời gian tìm quyết định xuống <10 phút; luôn kèm link provenance khi áp dụng.

---

## Problem Card #3 — Viết weekly progress note / meeting summary

**Problem (tóm tắt):** Ghi chú rời rạc sau meeting/tuần, tốn thời gian để biên tập thành summary rõ ràng và action items.

**Actor:** Researcher, note-taker.

**Current workflow (ASCII):**

```text
[Capture raw notes / audio]
    ↓
[(opt) Transcribe audio]
    ↓
[Organize notes -> results / risks / next]
    ↓
[Draft summary]
    ↓
[Assign owners & follow-up]
```

**Bottleneck:** Tổ chức và kiểm tra tính chính xác kỹ thuật; đảm bảo action owners rõ.

**Success metric:** Summary ready <30 phút sau meeting; action owners assigned và theo dõi.

---

Ghi chú: Tôi đã làm theo mẫu trong `02-deliverable-example.md`. Bạn muốn tôi tiếp tục mở rộng `02-group-problem-statement/` (research notes, quick validation, draft problem statement v0→v1) hay đồng bộ 2 problems còn lại sang format đầy đủ trước?
