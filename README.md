# 🎄 Christmas Piano Advent Tree / 圣诞钢琴日历树

A hand-gesture Christmas web game: gather the stars into a tree with your fists, watch the tree play and open days 1–12 of an advent calendar, then play the piano with your fingers to open days 13–24.

用手势玩的圣诞网页小游戏：双手握拳把星光聚成圣诞树，树先自动演奏、打开 1–12 天日历；之后你用手指弹钢琴，打开 13–24 天。

**Play / 试玩：** https://yllld8848lilyang.github.io/xmas-piano-tree/

- Open in Chrome on a computer and allow the camera. / 请用电脑 Chrome 打开，并允许摄像头。
- Hand tracking uses MediaPipe Hands (loaded online). / 手势识别使用在线加载的 MediaPipe Hands。
- No camera? Mouse and keyboard work too. / 没有摄像头也可以用鼠标和键盘玩。

Single-file app: everything is in `index.html`.

## For the developer / 开发者说明

- Calendar photos live in `photos/` as `p01.jpg` … `p21.jpg` (web-size copies, no EXIF). Days 22–24 reuse p19–p21. To change them, replace the files and update `PHOTO_COUNT` in `index.html`.
- 日历照片在 `photos/` 文件夹（压缩后的网页版，已去掉拍摄信息）。第 22–24 天重复最后 3 张。
