# Bài 5 - Thiết lập thư mục Web an toàn tại /opt/

## Kiểm tra quyền

ls -la /opt/my-app/

## Kiểm tra website

curl http://localhost:8080

## Kiểm tra ghi file bằng devops

echo "Update Test" >> /opt/my-app/html/index.html

## Kiểm tra log

tail /opt/my-app/logs/access.log