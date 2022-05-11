Cách sử dụng:
    Tải git từ link: https://www.git-scm.com/
    Xóa git init không cần thiết:
        git restore
    Các thao tác với github:
        HTTPS:
            git clone [Địa chỉ HTTPS]: lấy code từ github về project (Thực hiện lần đầu)
            git pull: Down code từ những lần tiếp theo
            git push:
                git status: Kiểm tra trạng thái của các file trong project
                Bước 1: Đẩy code lên local repo
                    git add: Thêm file vào tracked list bình thường sẽ dùng: git add . - dùng để push tất cả
                    git commit -m: đẩy lên local repo và thêm thông báo
                Bước 2:
                    git push: đẩy code lên server ...
                    
        SSH:
            https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh
        
