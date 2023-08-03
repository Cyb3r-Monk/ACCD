# AC&CD: Active C&C Detector

![ACCD](./images/ACCD.png)

AC&CD is a tool for detecting malicious beaconing activity. Current detection strategies rely on beacons using a fixed sleep and jitter configuration. However, in real attacks, the sleep and jitter configuration is often dynamic, meaning that attackers change the sleep and jitter configuration on the fly according to their needs, such as SOCKS tunneling, off-business hours, etc. AC&CD uses a different approach and finds potential beaconing activity where there is a certain period of time that the attackers are active on the keyboard and executing commands on the victim machine.