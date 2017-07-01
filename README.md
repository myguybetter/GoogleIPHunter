# Google IP Hunter

This project is mainly for collecting global google ips. Mostly Google Global Cache IPs (GGC), also with Official IPs.

GGC only provides with two kinds of certificates (gws - google.com & gvs - googlevideo.com).

You can check Google's Official GGC Distribution Map here: https://peering.google.com/#/infrastructure

## How you hunt for them?

By online searching.

## How to Use?

Try to scan the IP ranges by using multiple IP scanning tools (like gscan, gogotester etc.). Both available **gws** and **gvs** ips can be used in Google Cloud Engine Proxy Tools (goagent, goproxy etc.), but only **gws** ips can be used by hosts file.

## But, all contents are ENCRYPTED!

Yes, I encrypted them all (except China). Don't be surprised if you can't read the raw file.

To decrypt, you need to solve a riddle. Don't be a free rider. All files are encrypted with the same key.

You can view all **China** IP ranges without decrypting files. Enjoy.

## The riddle

Key: (6,5)(3,2), in English.

Hint: u=wu, n=nn.

Method: AES-256-ECB.

All salted. Try to use openssl.
