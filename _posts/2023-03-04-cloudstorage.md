---
layout: post
title: Paid Storage providers
---


| Provider                                            | Free Storage / BW | rclone support | 1GB/Month | 1TB/month | DL Bandwith GB | Extra/Notes |
| --------------------------------------------------- | ----------------- | -------------- | --------- | --------- | ----------- | ----------- |
| Backblaze B2                                        | 10GB  / 1GB            | S3, B2 (native)|  $0.005  | $5.12  |   $0.01  |   Class “B” transactions - $0.004 per 10,000 with 2,500 free per day. “C” transactions - $0.004 per 1,000 with 2,500 free per day. , Free BW via [BW Allience](https://www.backblaze.com/b2/integrations.html)   |
| Cloudflare R2                                       | 10 GB              | S3             | $0.015 |  $15.36  |   0.00 | Class A 1,000,000 / month, B 10,000,000 / month [source](https://www.cloudflare.com/products/r2/)|
| STORJ                                               | 25gb / 25gb       | S3             | 0.004  | $4  |  $0.007    |             |
| idrive E2                                           | 10 gb             | S3             | 0.004   |  $ 0.84 to 3.34 with 1 year plan  |  0.00      |  They have 1 year plan you can prepay  |
| Hetzner storagebox                                  | 0 gb              | SMB, FTP, SFTP, WEBDAV | - *from 0.003125*   |  from  3.20  |  0.00     |  monthly only, connection limit  |
| Hetzner Storageshare (nextcloud)                    | 0 gb              | WEBDAV         | - *from 0.00418*  |  from  4.29  |  0.00      |  Can prepay up to a year, connection limit  |
| Wasabi | 0 gb | S3 | - *aka 0.0069* | 6.99 | 0.00 | Fair usage free egress, minimum storage duration policy (90 days) [source](https://wasabi.com/paygo-pricing-faq/)








<script src='{{ '/public/js/tablesort.js' | absolute_url }}'></script>
