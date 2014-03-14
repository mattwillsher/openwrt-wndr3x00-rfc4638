Add RFC 4638/1500 MTU support to OpenWRT 12.09

In a check out of the OpenWRT source, 

* 600-ppp-rfc4638.patch goes in ppp/patches
* 655-MIPS-ath79-baby-jumbo-support.patch goes target/linux/ar71xx/patches-3.3


For trunk support, the ath79 patch is no longer need.
ppp 2.4.6 has been release too, which contains the ppp patch. I have a [work in progress](https://github.com/mattwillsher/openwrt-ppp246) patch set for getting 2.4.6 working in trunk.

