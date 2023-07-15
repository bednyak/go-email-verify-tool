# Go-email-verify-tool

### Run
```
go run main.go
```

### Test
Enter mailchimp.com and see result
```
mailchimp.com
[return_result] ---> mailchimp.com, true, true, v=spf1 include:servers.mcsv.net include:mail.zendesk.com include:_spf.google.com include:mailsenders.netsuite.com include:_spf.qualtrics.com ip4:199.33.145.1 ip4:199.33.145.32 ip4:35.176.132.251 ip4:52.60.115.116 ~all, true, v=DMARC1; p=reject; rua=mailto:19ezfriw@ag.dmarcian.com,mailto:dmarc_rua@emaildefense.proofpoint.com; ruf=mailto:19ezfriw@fr.dmarcian.com,mailto:dmarc_ruf@emaildefense.proofpoint.com;
```