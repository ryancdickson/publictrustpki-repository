---
title: Home
layout: landing
permalink: /
top: false

hero:
  heading: A repository for the U.S. Federal Public Trust TLS PKI
  content: This site contains information on the U.S. Federal Public Trust Transport Layer Security (TLS) Public Key Infrastructure (PKI), an infrastructure which supports automated issuance of digital certificates for Federal .mil and .gov web services.

  button:
    text: Learn more
    href: faq/#general
---

<section class="usa-section">
  <div class="usa-grid usa-content">
<div class="usa-width-one-whole">
## Current Documents
### Policies
- [U.S. Federal Public Trust TLS PKI Certificate Policy]({{site.baseurl}}/assets/cp.pdf){:target="blank"} <br>(PDF, February 2019)
- [United States Federal PKI X.509 Certification Practice Statement (CPS) for the U.S. Federal TLS Root Certificate Authority]({{site.baseurl}}/assets/root-cps.pdf){:target="blank"}<br>(PDF, March 2019)
- [U.S. Federal Public Trust TLS PKI Defense Information Systems Agency Subordinate CA Certificate Practices Statement]({{site.baseurl}}/assets/subordinate-cps.pdf){:target="blank"}<br>(PDF, March 2019) 

## CA Certificates
### Root CAs
<table>
  <thead>
    <tr>
      <th scope="col">Name</th>
      <th scope="col">Public Key</th>
      <th scope="col">Fingerprint (SHA1)</th>
      <th scope="col">Valid Until</th>
      <th scope="col">Links</th>
      <th scope="col">Tests</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Test US Federal TLS Root CA</th>
      <td>RSA 4096, SHA-256</td>
      <td>79:60:36:34:37:ef:3c:40:42:b0:e7:b6:b0:f9:af:15:c3:65:22:d4</td>
      <td>1/18/2038</td>
      <td><a href="{{site.baseurl}}/assets/test-tlsroot.cer" target="_blank">DER</a> <br> <a href="http://tlsroot.pki-lab.gov/tlsroot/test-tlsroot.crl" target="_blank">CRL</a></td>	  
      <td><a href="https://valid.tlsroot.pki-lab.gov" target="_blank">Valid</a> <br> <a href="https://revoked.tlsroot.pki-lab.gov" target="_blank">Revoked</a> <br> <a href="https://expired.tlsroot.pki-lab.gov" target="_blank">Expired</a></td>
    </tr>
   </tbody>
</table>

### Subordinate CAs
<table>
  <thead>
    <tr>
      <th scope="col">Issuer</th>
      <th scope="col">Name</th>
      <th scope="col">Public Key</th>
      <th scope="col">Fingerprint (SHA1)</th>
      <th scope="col">Valid Until</th>
      <th scope="col">Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Test US Federal TLS Root CA</th>
      <td>Test US Federal TLS CA 1</td>
      <td>RSA 2048, SHA-256</td>
      <td>97:12:56:7f:4f:da:e2:dc:87:9d:69:6d:57:f5:c1:25:a2:5e:91:3c</td>
      <td>8/14/2028</td>	  
      <td><a href="{{site.baseurl}}/assets/test-subordinate.cer" target="_blank">DER</a></td>	  
    </tr>
   </tbody>
</table>

## Audit Reports
[![webtrust-ca]({{site.baseurl}}/assets/img/webtrust-ca.png)](https://www.cpacanada.ca/webtrustseal?sealid=){:target="_blank"}
[![webtrust-baseline]({{site.baseurl}}/assets/img/webtrust-baseline.png)](https://www.cpacanada.ca/webtrustseal?sealid=){:target="_blank"}<br>

