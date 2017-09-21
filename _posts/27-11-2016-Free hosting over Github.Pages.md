---
layout: post
title:  "Free Hosting Over Github"
categories: wevdev
---
Author: Amit Singh Pharityal

<b>What is this article all about?</b><br>
Do you know you can have free hosting of your portfolio or blog like mine for free.Yes this is possible,
Github.Pages gives you this facility.You can develope your portfolio or any static website and host it over github.<br>
                            <b>JEKYLL</b>:jekyll is a tool that is integrated with github to help you create and manage your blog.
It only helps you in creating static websites.

<img src="/assets/jekyll.png" height="400" width="850" border="1px solid"/>

<b>How its done?</b>
First you need to download ruby which you can download from rubyinstaller.org/downloads/... which is shown in the screenshot below:

<img src="/assets/ruby.png" height="400" border="1px solid"/>

You always need to download devkits, highlighted in the following screenshot from the same page.
64bit if you a 64bit computer other wise 32bit.

<img src="/assets/devkit.png" height="400" width="850" border="1px solid"/>


Create a folder in C:/Devkit and extract the files there.
Then run command prompt and change directory to devkit, finally run the following commands<br>
<b>First Command:</b>
{% highlight ruby %}
	ruby dk.rb init
{% endhighlight %}
<b>Second Command:</b>
{% highlight ruby %}
	ruby dk.rb install
{% endhighlight %}
<b>Install Jekyll:</b>
{% highlight ruby %}
	gem install jekyll
{% endhighlight %}
<img src="/assets/rubyinstall.png" height="300"  border="1px solid"/>

gem install < package name > command of ruby  is used to install packages, if any error in missing packages use this command to install the following package.

Next just create a Project folder and change directory to that folder and start jekyll.


{% highlight ruby %}
	  jekyll new AmitPhartiyal

	  cd AmitPharityal

	  jekyll serve
{% endhighlight %}





