This section specifies the X.509 version 3 certificate profiles, version 2 Certificate Revocation List (CRL) profile, and Online Certificate Status Protocol (OCSP) Response profile for the U.S. Federal Public Trust TLS PKI Certificate Policy.  In cases where the profiles and Section 7 of this CP are in conflict, Section 7 takes precedence and is authoritative.

Certificates issued under this policy are categorized as CA Certificates, Subscriber Certificates or Infrastructure Certificates.  This Certificate Policy defines five (5) different types of certificates (See Section 1.1.3) and four associated certificate profiles.  

| **Category** | **Certificate Type**  | **Profile**  |
| :-------- | :----------------------- | :----------------------- |
| CA Certificate | Root CA Certificate | Self-Signed Root CA Certificate Profile |  
| CA Certificate | Subordinate CA Certificate | Subordinate CA Certificate Profile |
| Subscriber Certificate | Domain Validation TLS Server Authentication Certificates |  Server Authentication Certificate Profile |
| Subscriber Certificate | Organization Validation TLS Server Authentication Certificates |  Server Authentication Certificate Profile |
| Infrastructure Certificate | Delegated OCSP Responder Certificates |  Delegated OCSP Responder Certificate Profile |

There are two profiles covering the Certificate Revocation Lists and OCSP Responses.

| **Type** | **Profile**  |
| :-------- | :----------------------- |
| Certificate Revocation Lists |  CRL Profile |
| Online Certificate Status Protocol (OCSP) Responses | OCSP Response Profile |

{% include certificate-profile-root-CA.md %}  
{% include certificate-profile-subordinate-CA.md %}  
{% include certificate-profile-server-authentication.md %}  
{% include certificate-profile-OCSP-responder.md %}
{% include crl-profile.md %}
{% include ocsp-response-profile.md %}
