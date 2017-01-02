---
published: true
layout: post
author: me
title: "Removing a Retained message from the broker"
tagline:
excerpt: "Removing a Retained message from the MQTT broker"
---

# Removing a Retained message from the broker

<p>We can remove retained messages by publishing a zero length retained
message to the topic you wish to clear. For example, you could do it
with mosquitto_pub as follows:</p>

<p><code>mosquitto_pub -h [host] -t [topic] -r -n</code></p>

<p>Cheers,</p>
