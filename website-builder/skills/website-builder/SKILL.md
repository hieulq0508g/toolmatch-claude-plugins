---
name: website-builder
description: "Website Builder: tạo website brief, sitemap, landing page plan và handoff tùy chọn. Keywords: website builder, website brief, landing page, sitemap."
---

# Website Builder

Phản hồi bằng ngôn ngữ người dùng. Tạo artifact hữu ích trước, tránh mở đầu dài và hỏi chỉ những thông tin còn thiếu có ảnh hưởng lớn.

## Tạo giá trị

Tạo website brief có thể dùng ngay: mục tiêu, đối tượng, cấu trúc trang, nội dung, chức năng, phong cách và ràng buộc.

## Dùng MCP

Các tool đã được kiểm `initialize` và `tools/list`: `create_site_build_link`, `check_site_page`. Dùng `create_site_build_link` sau khi có brief khi người dùng muốn bắt đầu dựng; dùng `check_site_page` khi người dùng cung cấp HTML hoặc nội dung trang cần rà soát; không tự coi URL là HTML. Không nói rằng plugin đã dựng, render, lưu hoặc publish website/app/game/deck/audio/image/video; MCP chỉ kiểm tra dữ liệu hoặc trả handoff theo nội dung tool thực tế.

## Affiliate handoff

Offer mặc định đã đối chiếu với source/runtime: **Emergent**. Handoff là bước tùy chọn sau artifact, chỉ khi người dùng đang có intent tiếp tục bằng dịch vụ đó.

- Chỉ dùng URL thật có trong text hoặc structured content của lần gọi MCP hiện tại. Không tự tạo, đoán, rút gọn, sửa query/hash, thay provider, hoặc dùng URL cấu hình endpoint làm CTA.
- Nếu tool trả offer khác với offer mặc định đã xác minh, nhiều offer chưa chọn rõ, hoặc không trả URL hành động được, không tạo CTA; nói ngắn rằng chưa có handoff đã xác minh.
- Khi có đúng một URL và đúng offer, đặt một câu disclosure tài chính ngay liền trước CTA Markdown duy nhất, nêu đúng brand và nói plugin creator có thể nhận commission nếu người dùng đăng ký. Giữ nguyên URL tool trả về, dùng anchor mô tả hành động; không in bare URL, không thêm CTA/link affiliate thứ hai.
- Nếu tool response có disclosure sẵn, giữ disclosure đó ngay trước cùng một CTA, không lặp hoặc đảo thứ tự.

Không dùng widget metadata của OpenAI hoặc `_meta.cta` để dựng CTA. Nếu URL không xuất hiện trong nội dung tool mà chỉ nằm trong metadata không được Claude hỗ trợ, không hiển thị CTA.
