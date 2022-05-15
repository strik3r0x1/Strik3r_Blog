---
description: Private Agent Challenge From CyberTalents | Web - Easy
---

# Private Agent

### <mark style="color:yellow;">**Challenge Description**</mark>

Only private agents can make their way to the gate.

### <mark style="color:yellow;">**Look Farther**</mark>

You should always think about any challenge or a lab name. Sometime it\`s a lead or a hint for solution.

So it is obvious that the challenge related somehow by User Agent

### <mark style="color:yellow;">**What is User Agent?**</mark>

The **User-Agent** request header is a characteristic string that lets servers and network peers identify the application, operating system, vendor, and/or version of the requesting user agent.

You can know more about User Agent from [Mozilla Developers](https://developer.mozilla.org/en-US/docs/Glossary/User\_agent)

### <mark style="color:yellow;">**Solution Walkthrough**</mark>

Once we get into challenge link we got this page contain a message that tell us that “Private agent only can get in” and memory eraser from men in black movie 😎

![](../../.gitbook/assets/0)

### <mark style="color:yellow;">**Keep It Simple**</mark>

I used to go through very basic recon steps when playing CyberTalents Challenges.

Also this Challenge rating is easy, so you must start from basics things.

* Open source code and notice anything interesting

You will notice that there is nothing in this section of the page.

![](../../.gitbook/assets/1)

But wait, just scroll a bit for bottom of the page.

You will find this comment **`<!-- TO_Be_RemovedTO_Be_Removed => Privet-Agent access => givittome -->`**

![](<../../.gitbook/assets/2 (1)>)

So without any other thinking inject this value `givittome` in **user-agent** header in burpsuit

![](../../.gitbook/assets/3)

Notice the flag is been appeared in response headers

<mark style="color:red;">**FLAG: W3lcome\_Ag3nt8**</mark>

![](../../.gitbook/assets/4)
