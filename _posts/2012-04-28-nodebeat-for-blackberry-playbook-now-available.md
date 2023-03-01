---
id: 137
title: 'NodeBeat for BlackBerry PlayBook now available!'
date: '2012-04-28T18:00:28+01:00'
author: Laurence
layout: post
guid: 'http://epicwindmill.com/?p=137'
permalink: /2012/04/28/nodebeat-for-blackberry-playbook-now-available/
categories:
    - Blog
---

After receiving a BlackBerry PlayBook through the [developer offer](http://devblog.blackberry.com/2012/02/latest-blackberry-playbook-tablet-offer-for-android-developers/) in March, we started to look into the possibility of porting [NodeBeat](http://www.nodebeat.com/) to the PlayBook platform.

While it is a smaller tablet (7 inch) than the iPad (10 inch), it feels quite nice in the hand. Spec wise this device is [great](http://en.wikipedia.org/wiki/BlackBerry_PlayBook) (dual-core cpu, 1 GB ram, dedicated graphics chip), therefor it would be nice to test if the PlayBook would be a perfect platform to run NodeBeat on.

### Porting

Since NodeBeat is build on top of the popular [openFrameworks](http://www.openframeworks.cc/) (OF) platform, I [forked openFrameworks](https://github.com/falcon4ever/openFrameworks/tree/developPlayBook) and started to work on a new add-on for OF called [ofxQNX](http://www.multigesture.net/projects/ofxqnx/) to extend the current framework. While there initially were some difficulties with the audio part, [Seth](http://sethsandler.com/) managed to integrate SDL into ofxQNX (just for the audio) which now provides us with very low latency audio playback. More information about the [ofxQNX project](https://github.com/falcon4ever/openFrameworks/tree/developPlayBook/addons/ofxQNX) (it is open source!) and how you can use it in your own projects can be found on my [personal research blog](http://www.multigesture.net/2012/04/27/playbook-add-on-ofxqnx/).

### BB 10 Jam

With [NodeBeat](http://nodebeat.com/) as our (ofxQNX) guinea pig, we have been working pretty hard the past weeks to get NodeBeat up and running just in time for [BB 10 Jam](http://www.blackberryjamconference.com/). Since NodeBeat uses a lot of different OF features, it was a perfect way to test out ofxQNX and the stability of the add-on.

Below is some footage I shot of an early NodeBeat Beta running on the PlayBook (it basically lacks the UI). I love that compared to the Android build, this device is giving us much lower input and audio latencies which really enhance the experience.

<iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" frameborder="0" height="281" loading="lazy" src="https://www.youtube.com/embed/xhZ46PpccGQ?feature=oembed" title="NodeBeat running on BlackBerry Playbook Tablet" width="500"></iframe>

<del>We have submitted NodeBeat to [the BlackBerry AppWorld](https://twitter.com/#!/NodeBeat/status/195589029377486848) so hopefully it will be available soon for your listening pleasure!</del>

**\[Edit 29-apr\]**  
It’s [now available](https://twitter.com/#!/NodeBeat/status/196297798331797504) on the [BlackBerry Appworld](http://appworld.blackberry.com/webstore/content/106167/?lang=en) and is actually at the [top of the charts](https://twitter.com/#!/LaurenceMuller/status/196656657533648896)! It’s currently on sale for just 99ct!

### Screenshots

[![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000022-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000022.jpg) [![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000023-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000023.jpg)  
[![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000024-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000024.jpg) [![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000025-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000025.jpg)  
[![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000027-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000027.jpg) [![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000028-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000028.jpg)  
[![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000029-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000029.jpg) [![](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000030-300x175.jpg)](https://epicwindmill.com/wp-content/uploads/2012/01/IMG_00000030.jpg)

### More information

**Product website**:  
<http://nodebeat.com/>

**BlackBerry App World:**  
[NodeBeat for BlackBerry PlayBook](http://appworld.blackberry.com/webstore/content/106167/?lang=en)