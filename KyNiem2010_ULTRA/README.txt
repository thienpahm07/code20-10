KY NIEM 20-10 — BAN NANG CAP HIEU UNG

CHAY WEBSITE
1. Giai nen ZIP vao mot thu muc.
2. Mo thu muc bang VS Code.
3. Cai extension Live Server neu chua co.
4. Chuot phai index.html > Open with Live Server.
5. May can ket noi Internet de tai Three.js va OrbitControls.

CA NHAN HOA SO NGAY YEU VA LOI CHUC
Mo index.html, tim `window.KYNIEM_CONFIG` gan dau script thuong va sua:
- LOVE_DAYS: so ngay yeu that (mac dinh 365 de lam mau).
- WISH: loi chuc hien khi bam trai tim lon.
- PHOTO_CAPTIONS: loi nhan cho tung anh.
- TRACK_NAME va ARTIST_NAME: ten hien thi trong khung nhac.

THEM 10 ANH KY NIEM
Dat anh vao CUNG thu muc voi index.html, dat ten:
photo1.jpg, photo2.jpg, ... photo10.jpg
Neu anh co duoi PNG, mo index.html va doi `photo${i}.jpg` thanh `photo${i}.png`.
Anh se tu thay cac khung mau minh hoa.

THEM NHAC
Dat file nhac cua ban ten `music.mp3` cung thu muc voi index.html.
Nhac bat dau sau khi nhap dung LOVE_DAYS va bam Mo ky niem. Trinh duyet khong cho tu phat nhac truoc thao tac cua nguoi dung.

HIEU UNG
- Trai tim 3D co vat lieu bong va lop mat cat mau hong.
- 3.700 diem sang nen, dam hat mau tim hong, 94 trai tim 3D bay len.
- Quỹ dao sang, vong sang duoi san, cot sang, trai tim dap nhip.
- 10 khung anh chay quanh vung trung tam, hieu ung sao lap lanh, sao bang va trai tim DOM.
- Nhap loi chuc khi bam trai tim; bam tung anh de mo loi nhan rieng.

GHI CHU
Con so nhap chi la khoa don gian phia trinh duyet, khong phai bao mat thuc su.
Neu Three.js khong tai duoc, trang co hieu ung du phong 2D; kiem tra Internet va F12 > Console de xem loi.
