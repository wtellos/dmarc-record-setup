# dmarc-record-setup

DMARC helps protect your domain from email spoofing and phishing attacks by specifying how email receivers should handle messages that claim to be from your domain.
Location: cPanel > Zone Editor > manage domain > add new record (TXT)

Name: _dmarc.yourdomain.com <br>
TTL: 14400 <br>
Type: TXT <br>
Record: v=DMARC1; p=none; adkim=r; aspf=r;
