# Responsive Web Design (RWD)

- Thiết kế web thích ứng
- Đáp ứng giao diện web hoạt động tốt trên các thiết bị khác nhau (Dựa theo kích thước màn hình)
- Adaptive

## Breakpoint

- Điểm thay đổi
- Tại đây giao diện sẽ bị thay đổi
- Không có các breakpoint cố định cho mọi dự án, mà chỉ có các breakpoint phổ biến

* 576px
* 768px
* 992px
* 1200px
* 1400px

## Meta Viewport

- Viewport: Khung nhìn

## Media Queries

```css
@media all|screen|print and (min-width: minValue) and (max-width: maxValue) {
  selector {
    /*Code CSS*/
  }
}

@media screen and (max-width: 1399.98px) {
  /*Code CSS*/
}
@media screen and (max-width: 1199.98px) {
  /*Code CSS*/
}
@media screen and (max-width: 991.98px) {
  /*Code CSS*/
}
@media screen and (max-width: 767.98px) {
  /*Code CSS*/
}
@media screen and (max-width: 575.98px) {
  /*Code CSS*/
}
```

```css
@media screen and (min-width: 576px) {
  /*Code CSS*/
}
@media screen and (min-width: 768px) {
  /*Code CSS*/
}
@media screen and (min-width: 992px) {
  /*Code CSS*/
}
@media screen and (min-width: 1200px) {
  /*Code CSS*/
}
@media screen and (min-width: 1400px) {
  /*Code CSS*/
}
```
