# GET aHEAD
-------------------------------------------
## Description

```Find the flag being held on this server to get ahead of the competition ```
- http://mercury.picoctf.net:47967/

Даалгаварын нэрийг харвал *GET aHEAD* буюу http request method-той холбоотой байж болох санаа төрсөн.

![source ](https://github.com/ulambayar0511/picoCTFwriteups/blob/main/web/GET_aHEAD/ss/source.png)

*Даалгаварын source code-г харвал **GET** хүсэлтээр улаан өнгийг **POST** хүсэлтээр цэнхэр өнгийг сонгож байсан*

- curl -X POST http://mercury.picoctf.net:47967/ үр дүнд цэнхэр өнгө
- curl -X POST http://mercury.picoctf.net:47967/ үр дүнд улаан өнгө

- curl -X PUT,DELETE http://mercury.picoctf.net:47967/ үр дүнд ямар өнгийг харуулсан response ирэхгүй байсан.

### curl -I http://mercury.picoctf.net:47967/  HEAD request явуулж үзэхэд амжилттай flag-г олсон

![flag ](https://github.com/ulambayar0511/picoCTFwriteups/blob/main/web/GET_aHEAD/ss/flag.png)

## Дүгнэлт 

Энэхүү даалгаварын зорилго http request method харуулах зорилготой байсан





