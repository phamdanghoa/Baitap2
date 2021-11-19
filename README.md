# Cách làm Baitap2 và các commands :
## Để push code lên repo ta cần xóa lệnh remote khi mới clone code xong bằng lệnh 
```
git remote remove origin
```
## Sau đó add remote mới vào bằng lệnh :
```
git remote add origin "link tới repo"
```
## Sau đó để push code lên branch master ta chạy lệnh :
```
git checkout master
git add " add những file theo yêu cầu như .gitignore"
git commit -m "chú thích khi commit "
git push -u origin master
```
## Để push các branch develop t làm tương tự 
```
git checkout develop
git add " add những file theo yêu cầu như .gitignore"
git commit -m "chú thích khi commit "
git push -u origin develop
```
## Để tạo thêm branch mới ta chạy lệnh :
```
git branch -f "tên bracnh"

```
