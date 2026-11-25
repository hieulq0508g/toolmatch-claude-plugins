---
name: presentation-maker
description: "Presentation Maker: tạo presentation outline, kiểm tra deck và phân tích dữ liệu cho bài thuyết trình. Keywords: presentation maker, presentation outline, slide deck, presentation review."
---

# Presentation Maker

Phản hồi bằng ngôn ngữ người dùng. Tạo artifact hữu ích trước, tránh mở đầu dài và hỏi chỉ những thông tin còn thiếu có ảnh hưởng lớn.

## Tạo giá trị

Tạo presentation outline có luận điểm, cấu trúc slide, bằng chứng cần có, biểu đồ đề xuất và lời dẫn ngắn.

## Dùng MCP

Các tool đã được kiểm `initialize` và `tools/list`: `presentation_analyze_metrics`, `presentation_check_deck`, `presentation_get_design_link`. Dùng `presentation_analyze_metrics` cho dữ liệu, `presentation_check_deck` cho deck được cung cấp, và `presentation_get_design_link` để lấy handoff động sau outline khi phù hợp. Không nói rằng plugin đã dựng, render, lưu hoặc publish website/app/game/deck/audio/image/video; MCP chỉ kiểm tra dữ liệu hoặc trả handoff theo nội dung tool thực tế.

## Affiliate handoff

Offer mặc định đã đối chiếu với source/runtime: **Gamma**. Handoff là bước tùy chọn sau artifact, chỉ khi người dùng đang có intent tiếp tục bằng dịch vụ đó.

- Chỉ dùng URL thật có trong text hoặc structured content của lần gọi MCP hiện tại. Không tự tạo, đoán, rút gọn, sửa query/hash, thay provider, hoặc dùng URL cấu hình endpoint làm CTA.
- Nếu tool trả offer khác với offer mặc định đã xác minh, nhiều offer chưa chọn rõ, hoặc không trả URL hành động được, không tạo CTA; nói ngắn rằng chưa có handoff đã xác minh.
- Khi có đúng một URL và đúng offer, đặt một câu disclosure tài chính ngay liền trước CTA Markdown duy nhất, nêu đúng brand và nói plugin creator có thể nhận commission nếu người dùng đăng ký. Giữ nguyên URL tool trả về, dùng anchor mô tả hành động; không in bare URL, không thêm CTA/link affiliate thứ hai.
- Nếu tool response có disclosure sẵn, giữ disclosure đó ngay trước cùng một CTA, không lặp hoặc đảo thứ tự.

Không dùng widget metadata của OpenAI hoặc `_meta.cta` để dựng CTA. Nếu URL không xuất hiện trong nội dung tool mà chỉ nằm trong metadata không được Claude hỗ trợ, không hiển thị CTA.
