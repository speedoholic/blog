---
id: 1084
title: How to recover your Windows Password?
date: 2012-05-14T17:39:53+00:00
author: kushalashok
layout: post
guid: http://kushalashok.wordpress.com/?p=1084
permalink: /2012/05/14/how-to-recover-your-windows-password/
geo_latitude:
  - "30.359057"
geo_longitude:
  - "76.449078"
geo_accuracy:
  - "812"
geo_address:
  - punjabi university, patiala, punjab, india
geo_public:
  - "1"
tagazine-media:
  - 'a:7:{s:7:"primary";s:0:"";s:6:"images";a:0:{}s:6:"videos";a:0:{}s:11:"image_count";s:1:"0";s:6:"author";s:8:"14208831";s:7:"blog_id";s:8:"13804338";s:9:"mod_stamp";s:19:"2012-05-14 12:09:53";}'
publicize_results:
  - 'a:1:{s:7:"twitter";a:1:{i:70671171;a:2:{s:7:"user_id";s:11:"speedoholic";s:7:"post_id";s:18:"202007887755751424";}}}'
reddit:
  - 'a:2:{s:5:"count";i:0;s:4:"time";i:1343955899;}'
categories:
  - 'Ideas &amp; Tips'
---
I haven&#8217;t been using my laptop since the last 4 months and thus I forgot the administrator log-in password. Luckily I had created a guest account using which I logged in and started looking for ways by which I could recover my password. Initially I came across a few methods that involve <a title="crack password using command prompt" href="http://www.zimbio.com/Password+Recovery+Software/articles/Pf9x-NZ_1Lc/How+Break+Windows+Administrator+Password+DOS" target="_blank">running a command prompt</a>, but these methods required me to be logged in as one of the administrators.

After going through some <a class="zem_slink" title="YouTube" href="http://www.youtube.com/" rel="homepage" target="_blank">YouTube  videos</a> I finally came across the following:
  


<div class="jetpack-video-wrapper">
  <span class="embed-youtube" style="text-align:center; display: block;"></span>
</div>

This video gives you a complete demonstration about how you can use a bootable  cd to clear the administrator password.

You don&#8217;t need to install any software while you are logged in.

  1. Simply download the <a class="zem_slink" title="ZIP (file format)" href="http://en.wikipedia.org/wiki/ZIP_%28file_format%29" rel="wikipedia" target="_blank">.zip file</a> by following the <a title="tutorial" href="http://windows-server-training.com/windows-7-password-reset-recovery/" target="_blank">link</a> specified in the video description.
  2. Unzip the folder to get the .<a class="zem_slink" title="ISO image" href="http://en.wikipedia.org/wiki/ISO_image" rel="wikipedia" target="_blank">iso image</a>.
  3. Use this image to write a <a class="zem_slink" title="Compact Disc" href="http://en.wikipedia.org/wiki/Compact_Disc" rel="wikipedia" target="_blank">CD</a> using any <a class="zem_slink" title="List of optical disc authoring software" href="http://en.wikipedia.org/wiki/List_of_optical_disc_authoring_software" rel="wikipedia" target="_blank">CD burning software</a>.
  4. Reboot the system and change the primary <a class="zem_slink" title="Booting" href="http://en.wikipedia.org/wiki/Booting" rel="wikipedia" target="_blank">boot device</a> to CD ROM.
  5. When you leave the <a class="zem_slink" title="BIOS" href="http://en.wikipedia.org/wiki/BIOS" rel="wikipedia" target="_blank">BIOS settings</a> after saving them, you will be able to boot the CD which will direct you to the <a class="zem_slink" title="DOS" href="http://en.wikipedia.org/wiki/DOS" rel="wikipedia" target="_blank">DOS</a> mode.
  6. Rest is well demonstrated in the video.

This method worked like a charm and this is why I am writing this blog post to make a record of the same and probably help other users to work around their forgotten passwords.

So even if you don&#8217;t have a Guest account and your system is completely locked, you can buy a blank CD and visit your friend; or just go to any cyber cafe and follow the above procedure to make your magic CD. Just don&#8217;t forget to watch the video before you start with the process; otherwise you might end up like a magician being stuck in his magic closet.

_P.S.: You can also opt for a bootable flash drive but that generally involves installing a software which is not allowed in a guest account._