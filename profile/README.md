Xem task được giao ở [đây](https://github.com/orgs/fovigroup/projects/1)

Estimate: 1 point = 4 hour

## Thông tin hệ thống
- Folder Drive: [link](https://drive.google.com/drive/folders/1TPaqLsaAXfsHXttfWQJ3n4MC6U-Uzkr4?usp=sharing) 
- Design: [link](https://docs.google.com/spreadsheets/d/1aIMU-CQ_nd0S6hfSEEX0RGQFOOaYUzUGl0JYXaVeNqg/edit?usp=sharing)

### release/1.2.5 (18/06/2023)
- [ ] [UI-Admin-Dashboard] disable chart statistic dashboard with rule COLLECTOR
- [ ] [API] enhance data statistic by current user login
- [ ] [UI-Admin-Dashboard] show chart statistic access /post/:slug group by source

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

https://stackedit.io/app#
