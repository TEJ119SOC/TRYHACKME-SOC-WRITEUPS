Today I did my first real network traffic analysis using Wireshark.

Captured live DNS traffic from my own machine, extracted an IP address from a raw packet, and ran it through VirusTotal, AbuseIPDB, and Whois to build a threat intel verdict.

The IP came back flagged by 1 vendor with 84 abuse reports — looked suspicious at first.

But Whois showed it was registered to a legitimate organisation. False positive.

That decision-making process — cross-referencing multiple sources before making a call — is exactly what SOC analysts do every day.

Starting to understand it from the inside now.
