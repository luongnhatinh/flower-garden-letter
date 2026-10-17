# Âm thanh và lời bài hát

Các tệp được `index.html` sử dụng:

1. `until-i-found-you.mp3` — nhạc bìa “Until I Found You”; phát lặp và đồng bộ với lời bài hát trên bìa.
2. `pink-sweats.mp3` — nhạc nền vườn; phát lặp cùng âm gió và chim.
3. `gentle-love-piano-music.mp3` — [Gentle Love - Piano Music, Sonican](https://pixabay.com/music/modern-classical-gentle-love-piano-music-338060/).
4. `love-piano-emotional.mp3` — [Love Piano Emotional, PaulYudin](https://pixabay.com/music/wedding-love-piano-emotional-156905/).

Hai bài thư phát lần lượt rồi lặp playlist. Trình duyệt có thể yêu cầu người xem chạm hoặc nhấn phím trước khi phát âm thanh. Nhạc bìa giảm dần khi mở vườn; nhạc vườn giảm dần khi chuyển sang thư.

`lyrics-until-i-found-you.js` là nguồn dữ liệu duy nhất cho phần lời đồng bộ. Dùng tệp JavaScript để lời bài hát chạy giống nhau khi mở `index.html` trực tiếp và khi chạy qua máy chủ. Tệp `.lrc` chỉ là bản tham chiếu, không được trang nạp.

Khi gửi dự án, giữ `index.html` cùng thư mục `assets/audio/` và các tệp trên. Các MP3 trùng lặp nằm ở thư mục gốc không được trang sử dụng. Giữ thông tin nguồn và giấy phép của hai bản nhạc thư cùng dự án.
