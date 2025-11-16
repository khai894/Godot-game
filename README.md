
# Godot Game

Giới thiệu
Tetris là trò chơi xếp gạch kinh điển. Người chơi điều khiển các khối Tetromino rơi từ trên xuống. Khi một hàng được xếp đầy, hàng đó biến mất và người chơi nhận điểm.

Dự án này cung cấp:
Gameplay Tetris hoàn chỉnh
Logic sinh khối ngẫu nhiên
Xoay khối, di chuyển trái/phải, tăng tốc rơi
Hệ thống xóa hàng + tính điểm
Reset game (chơi lại)

🛠️ Công nghệ sử dụng
Godot Engine 4.x
GDScript
Node2D, TileMap, Timer…

🎮 Gameplay
Điều khiển:
Phím	Chức năng
← / →	Di chuyển khối
↓	Tăng tốc rơi
↑	Xoay khối
Space	Thả nhanh (hard drop) (tuỳ chọn)

Cơ chế:
Gạch rơi theo thời gian.
Khi gạch chạm đáy hoặc khối khác → khóa vị trí.
Nếu một hàng được lấp đầy → xóa hàng và + điểm.
Game kết thúc khi khối mới không thể spawn.


