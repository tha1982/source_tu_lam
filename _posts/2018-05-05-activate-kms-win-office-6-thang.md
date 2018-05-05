---
layout: post
title: Hướng dẫn activate server kms windows và office 6 tháng
subtitle: activate kms
bigimg: /img/path.jpg
tags: [hướng dẫn, popular]
date: 2018-05-05 10:00:00 -0700
lastupdated: 
---

**a. activate windows**

Mở cmd quyền Admin lên và chạy các dòng lệnh sau (copy và paste cho nhanh)

slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX

slmgr /skms kms.digiboy.ir

slmgr /ato

Trong đó:

+ skms.ddns.net là một máy chủ KMS, trường hợp bạn sử dụng máy chủ trên bị lỗi thì thay bằng một máy chủ bên dưới này nhé (Mình sẽ cập nhật liên tục):

kms.aglc.cc

kms.didichuxing.com

xykz.f3322.org

zh.us.to

kms.digiboy.ir

3rss.vicp.net:20439

+ W269N-WFGWX-YVC9B-4J6C9-T83GX là key cho bản Windows 10 Pro, danh sách key tương ứng với các phiên bản ngay dưới đây:

Windows 10 Home: TX9XD-98N7V-6WMQ6-BX7FG-H8Q99

Windows 10 Home N: 3KHY7-WNT83-DGQKR-F7HPR-844BM

Windows 10 Home Single Language: 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH

Windows 10 Home Country Specific: PVMJN-6DFY6-9CCP6-7BKTT-D3WVR

Windows10 Professional: W269N-WFGWX-YVC9B-4J6C9-T83GX

Windows10 Professional N: MH37W-N47XK-V7XM9-C7227-GCQG9

Windows10 Enterprise: NPPR9-FWDCX-D2C8J-H872K-2YT43

Windows10 Enterprise N: DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4

Windows10 Education: NW6C2-QMPVW-D7KKK-3GKT6-VCFB2

Windows10 Education N: 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ

Windows10 Enterprise2015 LTSB: WNMTR-4C88C-JK8YV-HQ7T2-76DF9

Windows10 Enterprise2015 LTSB N: 2F77B-TNFGY-69QQF-B8YKP-D69TJ

Windows10 Enterprise2016 LTSB: DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ

Windows10 Enterprise2016 LTSB N: QFFDN-GRT3P-VKWWX-X7T3R-8B639

<a href="https://imgur.com/sk7vt5z"><img src="https://i.imgur.com/sk7vt5z.png" title="source: imgur.com" /></a>

**b. activate office**

Vì máy chủ KMS chỉ chấp nhận cho Office 2016 VL, mà ở link tải mình đưa tất cả đều là Retail. Vì thế phải convert Retail qua VL.

link download

[Retail2VL32](https://app.box.com/s/jb5sa7j55xn0q9wwkebj90wvp52zvuu5)

[Retail2VL64](https://app.box.com/s/g6u2sdr5ecefq8em46s2z29u71438wdr)

Mở cmd (quyền admin lên)

+ Nếu dùng Office 2016 32bit trên máy tính chạy Windows 64 bit thì sử dụng lần lượt các lệnh:

cd C:\Program Files (x86)\Microsoft Office\Office16

cscript OSPP.VBS /inpkey:XQNVK-8JYDB-WJ9W3-YJ8YR-WFG99

cscript OSPP.VBS /sethst:kms.digiboy.ir

cscript OSPP.VBS /act

cscript OSPP.VBS /dstatus

+ Nếu dùng Office 2016 32 bit trên Windows 32 bit và Office 2016 64 bit trên Windows 64 bit thì cũng chạy lần lượt các lệnh:

cd C:\Program Files\Microsoft Office\Office16

cscript OSPP.VBS /inpkey:XQNVK-8JYDB-WJ9W3-YJ8YR-WFG99

cscript OSPP.VBS /sethst:kms.digiboy.ir

cscript OSPP.VBS /act

cscript OSPP.VBS /dstatus

Trong đó:

+ XQNVK-8JYDB-WJ9W3-YJ8YR-WFG99 là key Office 2016 Pro Plus. Nếu các bạn sử dụng các phiên bản Office như Visio, Project… thì thay key dưới đây vào:

Office Professional Plus 2016:      XQNVK-8JYDB-WJ9W3-YJ8YR-WFG99

Office Standard 2016 :                 JNRGM-WHDWX-FJJG3-K47QV-DRTFM

Project Professional 2016:               YG9NW-3K39V-2T3HJ-93F3Q-G83KT

Project Standard 2016:                 GNFHQ-F6YQM-KQDGJ-327XX-KQBVC

Visio Professional 2016:                  PD3PC-RHNGV-FXJ29-8JK7D-RJRJK

Visio Standard 2016:                     7WHWN-4T7MP-G96JF-G33KR-W8GF4

Access 2016:                                 GNH9Y-D2J4T-FJHGG-QRVH7-QPFDW

Excel 2016:                                      9C2PK-NWTVB-JMPW8-BFT28-7FTBF

OneNote 2016:                                DR92N-9HTF2-97XKM-XW2WJ-XW3J6

Outlook 2016:                               R69KK-NTPKF-7M3Q4-QYBHW-6MT9B

PowerPoint 2016:                           J7MQP-HNJ4Y-WJ7YM-PFYGF-BY6C6

Publisher 2016:                               F47MM-N3XJP-TQXJ9-BP99D-8K837

Skype for Business 2016:               869NQ-FJ69K-466HW-QYCP2-DDBV6

Word 2016:                                     WXY84-JN2Q9-RBCCQ-3Q3J3-3PFJ6

Sau khi chạy xong báo active thành công, hãy kiểm tra lại Office 2016 đã có bản quyền hay chưa.

+ kms.digiboy.ir là máy chủ KMS, có thể trong thời gian tới các bạn sử dụng máy chủ này thì máy chủ đã chết, vì thế các bạn có thể sử dụng các máy chủ KMS thay thế bên dưới này nhé:

kms.aglc.cc

kms.didichuxing.com

xykz.f3322.org

zh.us.to

skms.ddns.net

kms.digiboy.ir

3rss.vicp.net:20439
