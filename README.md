# email-testing-tools

## DKIM
* dkim.org - FAQ: http://www.dkim.org/info/dkim-faq.html#technical
* Instructions for checking DKIM TXT record with dig & several others: https://protodave.com/security/checking-your-dkim-dns-record/
  * dig google._domainkey.devpartners.com TXT
  * DKIM Key Checker: https://protodave.com/tools/dkim-key-checker/
  * "Selectors enable a single domain to have multiple keys. Some domains, like Twitter and eBay, use “dkim”. Google Apps domains typically use “google”. Others simply use “default”. Enter yours here. (Note: Do not include “_domainkey”)"
* DKIM Checker: http://dkimcore.org/tools/keycheck.html
* MX Toolbox: https://mxtoolbox.com/dkim.aspx

## SPF and DKIM
* Check both SPF and DKIM: https://www.mail-tester.com/spf-dkim-check

