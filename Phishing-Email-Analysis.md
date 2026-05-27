I analysed my first phishing email header as part of my hands-on SOC training.

The email was impersonating Apple Support. Here's what gave it away:

🚩 Sender domain was apple-account-verify.com — not apple.com
🚩 Reply-To was a protonmail address — legitimate companies don't do that
🚩 Sending IP traced back to a Tor exit node — attacker deliberately hiding their location
🚩 18/91 vendors flagged the IP on VirusTotal
🚩 6,629 abuse reports on AbuseIPDB with 100% confidence of abuse

The attacker worked hard to look convincing. But every phishing email leaves traces — in the domain, the headers, the IP, and the infrastructure behind it.

Knowing where to look makes all the difference.

IOCs identified:
• apple-account-verify.com
• 185.220.101.45
• support2024@protonmail.com
• for-privacy.net

hashtag#Cybersecurity hashtag#SOCAnalyst hashtag#PhishingAnalysis hashtag#BlueTeam hashtag#ThreatIntel hashtag#LearningInPublic hashtag#InfoSec
