# aws2asa
Take the Amazon list of AWS IP addresses and make them Cisco ASA friendly by converting the addresses from CIDR format to network masks and creating an object group with each network defined as an object.

This script owes a lot of thanks to Gian Paolo (routetonull) for o3652asa.py which was the inspiration and source of a lot of this code: https://github.com/routetonull/various/blob/master/o3652asa.py

To use this you need to download the JSON format AWS public IP address list locally and run this Python script against it:
https://docs.aws.amazon.com/general/latest/gr/aws-ip-ranges.html

As you can probably tell I am not a Python developer yet but despite being raw it does work and may save someone some time.

I'm sure there is plenty of potential to develop it further and improve on it!

I was using Python 2.7.6 to test/run this.
