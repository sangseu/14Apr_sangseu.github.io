---
published: true
layout: post
author: me
title: "Removing a retained message from the broker"
tagline:
excerpt: "Removing a retained message from the MQTT broker"
---

## Removing a retained message from the broker

<p>We can remove retained messages by publishing a zero length retained
message to the topic you wish to clear. For example, you could do it
with mosquitto_pub as follows:

<code>mosquitto_pub -h <host> -t <topic> -r -n</code>

Cheers,</p>
