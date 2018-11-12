# Quy tắc bay cho Git

🌍
*[English](README.md) ∙ [Español](README_es.md)  ∙  [Русский](README_ru.md) ∙ [简体中文](README_zh-CN.md)∙ [한국어](README_kr.md)*

###   "Quy tắc bay" là gì?

Môt [guide for astronauts](https://www.jsc.nasa.gov/news/columbia/fr_generic.pdf) (bây giờ các lập trình viên
sử dụng Git) về việc phải làm gì khi mọi thứ xảy ra sai.

> *Quy taccws chuyến bay* là cơ sở kiến thức khó kiếm được chỉ ghi trong sách hướng dẫn liệt kê, từng bước,
phải làm gì nếu X xẩy ra và tại sao. Về cơ bản, phải làm gì nếu X xẩy ra và tại sao. Về cơ bản, chúng là các quy trình
 vận hành tiêu chuẩn cụ thể theo từng kịch bản cụ thể. [...]
 
>   NASA đã nắm bắt những sai lầm, thảm họa và giải pháp cảu chugns tôi kể từ đầu những năm 1960, khi
các nhóm mặt đất thời đại Mercury bắt đầu thu thập "bài học kinh nghiệm" thành một bản tím tắt, bây giờ liệt kê hăng fnghinf tình huống có vấn đề.
 Và giải pháp của họ.
 
 &mdash; Chris Hadfield, *An Astronaut's Guide to Life*.
 
 #### CÁc quy ước cho tài liều này.
 
 Vì mục đích rõ ràng, tất cả các ví dụ trog tài liệu này sử dụng dấu nhắc bash tùy chỉnh  đẻ chỉ ra nhánh hiện tại
 và cps hay không ccs thay đổi theo giai đoạn. Nhánh được đặt trogn dấu ngoặc đơn và một `*` bên cạnh
 tên chi nhanh cho biết các thay đổi được tổ chức.
 
 Tất cả các lệnh sẽ hoạt động với ít nhất git phiên bản 2.13.0 [git website](https://www.git-scm.com/)
 để cập nhật phiên bản git cục bộ của bạn.
 

[![Tham gia chat tại https://gitter.im/k88hudson/git-flight-rules](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/k88hudson/git-flight-rules?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
<!-- BẮT ĐẦU doctoc tạo TOC, vui long giữ bình luận ở đây cho phép cập nhật tự động -->
<!-- Đừng chỉnh sử khu vực này, CÀI ĐẶT RE-UN doctoc ĐỂ CẬP NHẬT" -->
**Mục lục** *Được tạo bằng với [Doctoc](https://github.com/thlorenz/doctoc)*

  -[Kho chứ](#kho chứa)
  - [Tối muốn bắt đầu kho chứa cục bộ](#Tối-muốn-bắt-đầu-kho-chứa-cục-bộ)
  - [Tôi muốn mô phỏng một kho chứa từ xa](#tôi-muốn-mô-phỏng-kho-chứa-từ-xa)
  - [Editing Commits](#editing-commits)
  
 

 
 
 
