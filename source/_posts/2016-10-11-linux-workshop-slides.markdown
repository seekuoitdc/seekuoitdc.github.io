---
layout: post
title: "Slides from Introduction to Linux Workshop"
date: 2016-10-11 20:18:00 +0000
comments: true
categories: 
---

Thank you to everyone who came out to our Introduction to Linux workshop last Monday. As promised, [here](/2016_intro_linux_workshop/presentation.html)
are the slides from the presentation. For the people who were unable to log back into their Ubuntu user account after installing updates, one of our
members, who had this problem, was able to fix it through the following steps:

1. Select advanced options when booting Ubuntu \(The same option we used for creating the user account\)

2. Start linux in recovery mode \(Exactly how we created the user account \)

3. In the recovery menu choose *dpkg repair broken packages*

4. You will be asked if you allow the root filesystem to be remounted as read/write, choose *yes*

5. Dpkg will then begin repairing broken packages \(which resulted from the failed update\), this may take some time.

6. When this is complete you will be back at the recovery menu. Choose *resume* and Ubuntu should now work normally.

7. On all subsequent reboots, start Ubuntu normally \(without going into advanced options\)





