# Api Cho ChatBot Messenger

Facebook Đã Có Và Cho Người Dùng Tạo Api Cho Chatbots 😪 Tại Đey => [Đây Nè](https://developers.facebook.com/docs/messenger-platform).

### Api Này Có Thể Khiến Cho Bạn Payy Acc Như Cách Acc Bạn Chưa Từng Có, Hãy Chú Ý Nhé =))

Lưu Ý ! Nếu Bạn Muốn Sài Api Này Hãy Xem Document Tại [Đây Nè](https://github.com/Schmavery/facebook-chat-api).

## Tải Về 

Nếu Bạn Muốn Sử Dụng, Hãy Tải Nó Bằng Cách:
```bash
npm i fca-dongdz-remake
```
or
```bash
npm install fca-dongdz-remake
```

### Tải Bản Mới Nhất Hoặc Update

Nếu Bạn Muốn Sử Dụng Phiên Bản Mới Nhất Hay Cập Nhật Thì Hãy Vô Terminal Hoặc Command Promt Nhập :
```bash
npm install fca-dongdz-remake@latest
```
Hoặc
```bash
npm i fca-dongdz-remake@latest
```

## Nếu Bạn Muốn Test Api 

Lợi Ích Cho Việc Này Thì Bạn Sẽ Không Tốn Thời Gian Pay Acc Và Có Acc 😪
Hãy Sử Dụng Với Tài Khoản Thử Nghiệm => [Facebook Whitehat Accounts](https://www.facebook.com/whitehat/accounts/).

## Cài Đặt Cho Mirai: 

Bạn Cần Vô File Mirai.js,Sau Đó Tìm Đến Dòng
```js
    var login = require('tùy bot'); 
    /* Có thể là :
        var login = require('@maihuybao/fca-Unofficial');
        var login = require('fca-xuyen-get');
        var login = require('fca-unofficial-force');
    ...   
    */
```

Và Thay Nó Bằng:

```js
    var login = require('fca-dongdz-remake')
```

Sau Đó Thì Chạy Bình Thường Thôi  !

## Tự Nghiên Cứu

Nếu Bạn Muốn Tự Nghiên Cứu Hoặc Tạo Bot Cho Riêng Bạn Thì Bạn Hãy Vô Cái Này Đọc Chức Năng Của Nó Và Cách Sử Dụng => [Link](https://github.com/Schmavery/facebook-chat-api#Unofficial%20Facebook%20Chat%20API)

------------------------------------

__Hướng Dẫn Với Appstate__

```js
const fs = require("fs");
const login = require("fca-dongdz-remake");

var credentials = {email: "FB_EMAIL", password: "FB_PASSWORD"}; // thông tin tk

login(credentials, (err, api) => {
    if(err) return console.error(err);
    // đăng nhập
    fs.writeFileSync('appstate.json', JSON.stringify(api.getAppState(), null,'\t')); //tạo appstate
});
```

Hoặc Dễ Dàng Hơn ( Chuyên Nghiệp ) Bạn Có Thể Dùng => [c3c-fbstate](https://github.com/c3cbot/c3c-fbstate) Để Lấy Fbstate And Rename Lại Thành Apstate Cũng Được ! (appstate.json)

------------------------------------

## FAQS

FAQS => [Link](https://github.com/Schmavery/facebook-chat-api#FAQS)
