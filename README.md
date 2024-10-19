# Umi-OCR-server

## clone 本项目 到 /opt
桌面用户可 复制 Umi-OCR.desktop /usr/share/applicaionts

## 通过Docker 构建服务 
https://github.com/hiroi-sora/Umi-OCR_runtime_linux/blob/main/README-docker.md

构建为 umi-ocr-paddle

启动容器，不要删除 接续使用
```bash
docker run -d --name umi-ocr \
    -e HEADLESS=true \
    -p 1224:1224 \
    umi-ocr-paddle
```


## api参考
https://github.com/hiroi-sora/Umi-OCR/blob/main/docs/http/api_ocr.md#/api/ocr/get_options

## index.html
简易接口
![image](https://github.com/user-attachments/assets/c6f964b4-69b4-48f0-a3db-6a737105cdcd)
