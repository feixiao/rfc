# rfc
rfc学习翻译以及实现整理

### RTP

#### 协议

+ [RFC 3550 - RTP: A Transport Protocol for Real-Time Applications ](https://tools.ietf.org/html/rfc3550)

+ [RFC3551 - RTP Profile for Audio and Video Conferences with Minimal Control](https://tools.ietf.org/html/rfc3551)

+ [RFC3611 - RTP Control Protocol Extended Reports (RTCP XR)](https://tools.ietf.org/html/rfc3611)

+ [RFC3711 - The Secure Real-time Transport Protocol (SRTP) ](https://tools.ietf.org/html/rfc3711)

+ [RFC4585 - Extended RTP Profile for Real-time Transport Control Protocol (RTCP)-Based Feedback (RTP/AVPF) ](https://tools.ietf.org/html/rfc4585)

+ [RFC5124 - Extended Secure RTP Profile for Real-time Transport Control Protocol (RTCP)-Based Feedback (RTP/SAVPF) ](https://tools.ietf.org/html/rfc5124)

+ [RFC7741 - RTP Payload Format for VP8 Video](https://tools.ietf.org/html/rfc7741)

+ [RFC6184 - RTP Payload Format for H.264 Video](https://tools.ietf.org/html/rfc6184)

+ [RFC4566 - SDP: Session Description Protocol](https://tools.ietf.org/html/rfc4566)

+ [RFC 5450 - Transmission Time Offsets in RTP Streams](https://tools.ietf.org/html/rfc5450)

+ [RFC 5104 - Codec Control Messages in the RTP Audio-Visual Profile with Feedback (AVPF) ](https://tools.ietf.org/html/rfc5104)

  ​


#### 开源实现

+ [ortp](https://github.com/BelledonneCommunications/ortp)   C语言实现。


+ [jrtp](http://research.edm.uhasselt.be/jori/page/CS/Jrtplib.html)  C++实现。



### Interactive Connectivity Establishment (ICE)

#### 协议

+ [RFC 5245 - Interactive Connectivity Establishment (ICE): A Protocol for Network Address Translator (NAT) Traversal for  Offer/Answer Protocols](https://tools.ietf.org/html/rfc5245)
+ [RFC 3489 - STUN - Simple Traversal of User Datagram Protocol (UDP)  Through Network Address Translators (NATs)](https://tools.ietf.org/html/rfc3489)
+ [RFC 5389 - Session Traversal Utilities for NAT (STUN)](https://tools.ietf.org/html/rfc5389)
+ [RFC 5766 - Traversal Using Relays around NAT (TURN): Relay Extensions to Session Traversal Utilities for NAT (STUN)](https://tools.ietf.org/html/rfc5766)

#### 开源实现

+ [libnice](https://nice.freedesktop.org/wiki/)



### STUN & TURN

#### 协议

- [RFC 3489 - STUN - Simple Traversal of User Datagram Protocol (UDP)  Through Network Address Translators (NATs)](https://tools.ietf.org/html/rfc3489)
- [RFC 5389 - Session Traversal Utilities for NAT (STUN)](https://tools.ietf.org/html/rfc5389)
- [RFC 5766 - Traversal Using Relays around NAT (TURN): Relay Extensions to Session Traversal Utilities for NAT (STUN)](https://tools.ietf.org/html/rfc5766)

#### 开源实现

+ [Trickle ICE](https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice/)  用于测试**STUN/TURN服务器** 的工具

+ [coturn](https://github.com/coturn/coturn)  开源的**STUN/TURN服务器** 服务器

  ​
