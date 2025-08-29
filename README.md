简介
主要运用于批量测试时候的多IP请求同一路径下的情况，也可以直接使用不切换工具查看响应包。


功能
<img width="803" height="326" alt="image" src="https://github.com/user-attachments/assets/37f8403d-db7e-4a42-81d3-9c41c46980ca" />



常用语句
./ipfget -f ' URL文件路径' -p http://127.0.0.1:8080 -path /admin -q
<img width="1228" height="448" alt="image" src="https://github.com/user-attachments/assets/1087b8ae-3056-44c2-b58f-896dbe069ee4" />


缺陷，配置代时会导致无响应的返回200
