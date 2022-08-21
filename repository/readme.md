# TrusAuth Public-Key Infrastructure (PKI) & OID Adminstration
<!--
IANA REQUEST-99711
IANA MODIFY-11368
-->
Document Version: 2.0

TrusAuth Root OID is: `1.3.6.1.4.1.58723`

This page is used to publish the information about OID distribution and the details of OID.

Latest: 08/21/2022 UTC

## OID Distribution

- trusauth-inc(0)
- certificate-policies(1)
  - extended-validation(1)
    - SSL(1)
    - CodeSigning(2)
  - organization-validation(2)
    - SSL(1)
  - domain-validation(3)
    - SSL(1)
  - individual-validation(4)
    - SSL(1)
  - codesigning(10)
    - certificate(1)
  - intranet-validation(20)
  - test-unverified(30)
  - ocsp(50)
    - certificate(1)
- certificate-extensions(2)
  - union-verify-list(50)
- certificate-categories(3)
  - id-card-verify(100)
- union-verify(250)
  - version(1)
  - subject(2)
  - provider(3)
    - pub-key-hash(1)
    - priv-key-hash(2)
  - timestamp(4)

## OID Information
### certificate-policies(1)
Discription: TrusAuth Certificate Policies (CP) and Certification Practice Statement (CPS)<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>
#### extended-validation(1)
Discription: Extended Validation (EV) <br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>
##### SSL(1)
Discription: Secure Sockets Layer (SSL) Extended Validation (EV) policy<br>
##### CodeSigning(2)
Discription: Code signing Extended Validation (EV) policy<br>

#### organization-validation(2)
Discription: Organization Validation (OV) policy<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>
##### SSL(1)
Discription: Secure Sockets Layer (SSL) Organization Validation (OV) policy<br>

#### domain-validation(3)
Discription: Domain Validation (DV) policy<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>
##### SSL(1)
Discription: Secure Sockets Layer (SSL) Domain Validation (DV) policy<br>

#### individual-validation(4)
Discription: Individual Validation (IV) policy<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>
##### SSL(1)
Discription: Secure Sockets Layer (SSL) Individual Validation (IV) policy<br>

#### codesigning(10)
Discription: Code Signing policy<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>
##### certificate(1)
Discription: Code signing certificate policy<br>

#### intranet-validation(20)
Discription: Intranet Validation (INV) policy<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>

#### test-unverified(30)
Discription: Unverified certificate policy<br>

#### ocsp(50)
Discription: Online Certificate Status Procotol (OCSP) policy<br>
##### certificate(1)
Discription: Online Certificate Status Procotol (OCSP) response signing certificate policy<br>

### certificate-extensions(2)
Discription: X.509 Certificate Extensions<br>
#### union-verify-list(50)
Discription: TrusAuth Union Verify (UV) List Extension<br>

### certificate-categories(3)
Discription: TrusAuth ID Card Verify (IDCV) Extended Key Usage (EKU)<br>
#### id-card-verify(100)
Discription: TrusAuth ID Card Verify (IDCV) Extended Key Usage (EKU)<br>
Information: See [TrusAuth OID and Public-Key Infrastructure (PKI) Adminstration Page](https://www.trusauth.eu.org/oid/)<br>

### union-verify(250)
Discription: TrusAuth X.509 Extension Union Verify (UV) Objects<br>
#### version(1)
Discription: TrusAuth X.509 Extension Union Verify (UV) version<br>
#### subject(2)
Discription: TrusAuth X.509 Extension Union Verify (UV) subject<br>
#### provider(3)
Discription: TrusAuth X.509 Extension Union Verify (UV) provider<br>
##### pub-key-hash(1)
Discription: TrusAuth X.509 Extension Union Verify (UV) public key hash<br>
##### priv-key-hash(2)
Discription: TrusAuth X.509 Extension Union Verify (UV) private key hash<br>
#### timestamp(4)
Discription: TrusAuth X.509 Extension Union Verify (UV) timestamp<br>

