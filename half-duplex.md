# Half Duplex

The device must wait before sending a Frame if it is currently receiving a frame. It can either Send or Receive at a time. \(E.g. Walkie-Talkie\)

*  **When Half Duplex is enabled it enables CSMA/CD \[\[202011231920 CSMA-CD\]\] because one can either send/receive at a time in Half Duplex settings. If however both send at the send time then collision can occur.** 
* HUB is a Half Duplex device because it is a dumb device & broadcasts all the received frame to all the other ports & if it receiving any frame at the same instance then collisions are bound to happen. Hence, HUB uses Half Duplex with the help of CSMA/CD. 
* On Full Duplex side you will see Late Collisions / Buffer overloading.
* Autonegotiation \[\[202012101226 Autonegotiation\]\] failure leads to Duplex Mismatch \[\[202012110911 Duplex Mismatch\]\]

## Reference:

* CCNA 200-301 OCG, Volume 1, Pg. 160 - Wendell Odom.
* [https://courses.davidbombal.com/courses/267624/lectures/4152523](https://courses.davidbombal.com/courses/267624/lectures/4152523)
