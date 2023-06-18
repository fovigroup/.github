Xem task được giao ở [đây](https://github.com/orgs/fovigroup/projects/1)

Estimate: 1 point = 4 hour

## Thông tin hệ thống
- Folder Drive: [link](https://drive.google.com/drive/folders/1TPaqLsaAXfsHXttfWQJ3n4MC6U-Uzkr4?usp=sharing) 
- Design: [link](https://docs.google.com/spreadsheets/d/1aIMU-CQ_nd0S6hfSEEX0RGQFOOaYUzUGl0JYXaVeNqg/edit?usp=sharing)

### release/1.2.7 (25/06/2023)
- [ ] [API] add logic refresh token
- [ ] [UI-Auth] implement refresh token when access token expried

### release/1.2.6 (18/06/2023)
- [API] Hotfix some bug
- [UI-Admin] Hotfix some bug

### release/1.2.5 (18/06/2023)
- [x] [UI-Admin-Dashboard] disable chart statistic dashboard with rule COLLECTOR
- [x] [API] enhance data statistic by current user login
- [x] [#8](https://github.com/fovigroup/fovi-admin-view/issues/8) [UI-Admin-Dashboard] show chart statistic access /post/:slug group by source
- [x] [#207](https://github.com/fovigroup/fovi-server/issues/207) [API] get list all user
- [x] [#15](https://github.com/fovigroup/fovi-admin-view/issues/15) [UI-Admin-Event] filter by author
- [x] [#16](https://github.com/fovigroup/fovi-admin-view/issues/16) [UI-Admin-Event] add button publish Event when edit with role Admin
- [x] [UI-Auth] verify token expired

### release/1.2.4 (11/06/2023)
- UI Admin enhance
  - [UI-Admin-Event] enhance change image, filter by time for column createdTime, startTime, filter by title, content
  - [API] add endpoint upload image for Post
  - [API] add endpoint remove image
- [API] enhance get list Post filter by current user login (permission)
- Crawl Post from url and call API create Post raw
  - [API] add endpoint create post raw
  - [CRAWL] setup file get info newspaper from url and call api create Post raw

### Backlog
- enhance crawl Event with RSS --> user crawl-rss (PhuongHX bị miss deadline)
  - dựa vào dữ liệu fovi để tạo tập test
  - dựa vào từ khóa trong file plan excel a Chức đã note
  - thêm từ khóa trong mongodb vào collection url
- khi chỉnh sửa Event và submitted, khi reload page cần active, scroll đến event đó

https://stackedit.io/app#
