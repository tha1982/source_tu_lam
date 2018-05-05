---
layout: post
title: Hướng dẫn cài đặt office 365 offline
subtitle: cài office 365
bigimg: /img/path.jpg
tags: [hướng dẫn, popular]
date: 2018-05-05 10:00:00 -0700
lastupdated: 
---

**a. Ở bài viết này mình chỉ hướng dẫn cài đặt 2 ứng dụng là: word và excel. Bạn nào có nhu cầu cài đặt thêm ứng dụng thì xem ở mục (b) tùy chọn cài đặt office 365**

Tạo thư mục office365 ở ổ C:\office365 và vào [download software Microsoft](https://tb.rg-adguard.net/index.php) tải file O365ProPlusRetail.img rồi giải nén file này bằng winrar (chỉ giải nén thư mục office) vào thư mục C:\Office365

<a href="https://imgur.com/4L2K1sO"><img src="https://i.imgur.com/4L2K1sO.png" title="source: imgur.com" /></a>

Mở thư mục office vừa giải nén và xóa 3 file: setup32.exe; setup64.exe; C2RfireFlyData.xml

<a href="https://imgur.com/XgKvipE"><img src="https://i.imgur.com/XgKvipE.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/PHDwAd6"><img src="https://i.imgur.com/PHDwAd6.png" title="source: imgur.com" /></a>

Copy file configuration.xml và setup.exe có trong file build setup 64.rar vào thư mục office365

<a href="https://imgur.com/zvUffQO"><img src="https://i.imgur.com/zvUffQO.png" title="source: imgur.com" /></a>

Mở CMD lên với quyền Admin, gõ vào lần lượt các lệnh sau:

Code:

cd c:\\office365 [Enter]

setup /configure configuration.xml [Enter]

[LƯU Ý] : không tắt CMD trong suốt quá trình cài đặt.

Link download

[build setup 32 bit](https://app.box.com/s/oer76fgh2i4qxhbcab7t2c9ngsbs0qpy)

[build setup 64 bit](https://app.box.com/s/d6v6fr7nrj5i0zi3xbuqu7m3z6kp3u9h)

[configuration 32 bit](https://app.box.com/s/0cpt8x4m6kidic2k5h4aoybl7pzf9m7k)

[configuration 64 bit](https://app.box.com/s/2ud4h3m0utv34gr3ftee8pphquixazta)

**b. Tùy chọn cài đặt office 365**

Bạn dùng notepad mở file configuration.xml và copy đoạn code sau:

<Configuration>

      <Add OfficeClientEdition="64">

        <Product ID="O365ProPlusRetail">

        <Language ID="en-us" />

		<ExcludeApp ID="InfoPath" />

		<ExcludeApp ID="Access" />

        		<ExcludeApp ID="Lync" />

        		<ExcludeApp ID="OneNote" />

        		<ExcludeApp ID="Outlook" />

        		<ExcludeApp ID="Project" />

        		<ExcludeApp ID="Publisher" />

       		<ExcludeApp ID="SharePointDesigner" />

         		<ExcludeApp ID="Visio" />

		<ExcludeApp ID="Powerpoint" />

		<ExcludeApp ID="Onedrive" />

         		<ExcludeApp ID="Groove" />

        </Product>

      </Add>

<Updates Enabled="TRUE" />

<Display Level="Full" AcceptEULA="TRUE" />

<Property Name="AUTOACTIVATE" Value="1" />

</Configuration>

Ở đây bạn chỉ cần chú ý <ExcludeApp ID="Groove" />, nghĩa là ta sẽ không cài Skype for Business. Nếu bạn muốn để lại Skype for Business thì bỏ dòng <ExcludeApp ID="Groove" />. Tương tự cho Access, Infopath .... Chỉnh sủa xong thì chỉ việc lưu lại thôi.

<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = 'https://connect.facebook.net/vi_VN/sdk.js#xfbml=1&version=v2.12';
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<div class="fb-comments" data-href="https://github.com/tha1982/tha1982.github.io/edit/master/_posts/2018-05-05-cai-office-365-offline.md" data-numposts="5"></div>
