### ✅ Nguyễn Văn A: Add code lần đầu và đưa thẳng lên git

```javascript
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tuhocvn/TeamAB.git
git push -u origin main
```

---

### ✅ Nguyễn Văn B: Tạo thư mục dự án

```javascript
git init
git remote add origin https://github.com/tuhocvn/TeamAB.git
git branch -M main
git pull origin main
```

khi A có thay đổi ví dụ trong index.html và push lên git mà ông B cũng thay đổi trong index.html cùng một dòng thì ông ông B sẽ gặp xung đột thì B sẽ pull về trước kéo code về thì gặp xung đột và có thể chọn AcceptCurrent hoặc các kế tiếp là code gốc mà ông A update và sau khi nhấn thì chọn Resolve in Merge editor → Complete Merge
