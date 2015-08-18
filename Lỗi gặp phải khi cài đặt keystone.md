###Lỗi `authorization failed: an unexpected error prevented the server from fulfilling your request. (http 500)`
- Trong file cấu hình /etc/keystone/keystone.conf, session [Default] có thể bị sai:
    <ul>
    <li>Provider</li>
    <li>Driver</li>
    </ul>

###Chú ý:
- không nhất thiết phải chạy câu lệnh: `openssl rand -hex 10` để generate ra một token có độ dài là 1 chuỗi có 10 ký tự ngẫu nhiên
- Token có thể thay thế bằng bất kỳ một chuỗi nào.
