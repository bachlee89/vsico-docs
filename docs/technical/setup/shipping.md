---
title: Phần mềm Shipping
parent: Cài đặt phần mềm
---
# Install VSICO Shipping on Local Environment
## Prerequisites
### Application requirements

To install VSICO Shipping on your local, you need to install the following applications:
 - [Docker](https://docs.docker.com/engine/install/)
 - [Composer](https://getcomposer.org/doc/00-intro.md)
 - [Git](https://git-scm.com/downloads)

## Install Steps
1, Download source code from github:

{% highlight some_language %}
git clone git@github.com:bachlee89/vsico-shipping.git
{% endhighlight %}

2, Run docker-compose command:

{% highlight some_language %}
cd vsico-shipping && docker-composer up --build -d
{% endhighlight %}

3, Edit hosts file
- On Windows
{% highlight some_language %}
C:\Windows\System32\Drivers\etc\hosts
{% endhighlight %}
- On Mac, Linux
{% highlight some_language %}
sudo vi \etc\hosts
{% endhighlight %}
- Add the following IP addresses:
{% highlight some_language %}
127.0.0.1 vsico-customer.local
127.0.0.1 vsico-admin.local
127.0.0.1 vsico-partner.local
{% endhighlight %}
- Open your browser and visit: 
{% highlight some_language %}
Customer page http://vsico-customer.local:8888
Partner page: http://vsico-partner.local:8888
Admin page: http://vsico-admin.local:8888
{% endhighlight %}