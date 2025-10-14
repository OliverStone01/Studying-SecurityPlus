#### 🎓 Professor Messer Study Notes

##  Web Filtering - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/I_c0D49uCwQ?si=6AIOuKkoJr429iYC)

### Notes

Content filtering can be done using a content filter. These are also known as URL filters or website category filtering. 

Sometimes these a setup to control what data is going in and out of an organisation. Especially if the organisation has sensitive data on their systems.

These are also used to block inappropriate content like not safe for work context. These are used as parental controls. 

You can also set these up to prevent users visiting know evil sites that contain malware. 

URL filters scan the URL (Uniform Resource Locator), which are also called URI (Uniform Resource Identifier). It then compares this url to an allow or block list that is setup to prevent access to those specific urls.

A block list allows all sites except those on the list.

An allow list only allows the sites on the list to be accessed. 

To make this easier, we can group categories to block all sites that contain information on travel for example. 

These devices were commonly their own unit with their own rules and policies. Now they are mostly build in to NGFW and just need the policies setting. 

Agent based firewalls that do URL filtering are placed on the users device because they may be working from home so it is best to secure all the devices as well as the network.

This allows the user to travel and connect to any network and they will be protected as long as they are using that device and the software is up to date. 

A proxy is a device that sits between users and an external network. This allows you to control the flow of traffic.

When the user requests a website to the network, this request travels to the proxy and the proxy makes the request and checks for any Malicious code on the returned data and then passes this data back to the device that made the request.

With a proxy, you can cache this returned data so that if the request is made again, the proxy can immediately respond with the data from the previous request.

Proxies also allow you to set up limit control which controls which device is able to access the internet. 

With some applications, we have to tell the device to use a proxy. This is referred to as an explicit proxy. 

Because some proxies work with out the end user realising, these proxies are known as a transparent proxy

A forward proxy is one that forwards data requests from the client to the internet and returns the data back to the client. This is sometimes known as an internal proxy. 

This proxy can then preform url filtering and detect and block malware.

Some content filter are able to look at the reputation of sites you try to access and can make a decision based on the reputation of that site. 

The types of risks range from: trustworthy, low risk, medium risk, suspicious, and high risk.

This process is automated by scanning the entire website and making a decision. You can also manually set the reputation if you do not agree with the automated outcome. 

DNS filtering is done before connecting to a website. This device blocks urls that it knowns are bad and contain malware. 

There are commercial and public lists that the DNS server uses.
