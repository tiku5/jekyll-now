---
layout: post
title: Python Instagram video downloader\n
---

![Instagram Image](/images/index.jpeg)

<br><br>

A little program coded by me and helped with the Regex by *someone* , its a simple powerfull script to download only videos from Instagram posts

You only will need the ID of the post, be sure its a video, not a image. Eitherwise the script will tell you if its a IMG or MP4.

Script: https://github.com/tiku5/instagram_video_downloader/blob/master/ig_down.py

{% highlight python %}
++++ Instagram Video Downloader by Bar. ++++
Uso: ./ig_down.py id_post name_local_video.
{% endhighlight %}

<br><br>

If we want to download this video => https://www.instagram.com/p/Bxu2132IoII/, we follow the next steps.

{% highlight python %}
> python3 ./ig_down.py Bxu2132IoII videodownload.mp4
++++ Instagram Video Downloader by Bar. ++++
[*] Link Video Found/Encontrado!
[+] HTTP Response:200
[+] Downloading/Bajando Video!
Video in:/home/nano/Desktop/8/videodownload.mp4
{% endhighlight %}

Then open your download mp4 =)
