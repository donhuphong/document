# Document
  - docker command
    
##  Docker_Command
```bash 
    # Va`o 1 service java
    docker run --rm -it --entrypoint /bin/bash hub.abc.vn/payment-integrations:gag216a-local
    # Kiểm tra phiên bản Docker 
    docker --version
    
    # hoặc muốn show chi tiết hơn
    docker info
    
    # Liệt kê các image
    # bỏ param -a đi thì sẽ chỉ show image đang run  
    docker images -a
      
    # Tải về 1 image từ hub.docker.com
    docker pull nameimage:tag
    
    # Liệt kê các container đang chạy
    docker ps
    
    # Liệt kê tất cả các container 
    docker ps -a
```
