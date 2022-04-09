# TrusAuth OIDs Distribution Adminstration
<!--
IANA REQUEST-99711
IANA MODIFY-11368
-->
Private Enterprise Number (PEN) is: `58723`

Root OID number is: `1.3.6.1.4.1.58723`

## Distribution

- trusauth-inc(0)
- certificate-policies(1)
  - extended-validation(1)
    - SSL(1)
    - CodeSigning(2)
  - organization-validation(2)
  - domain-validation(3)
  - individual-validation(4)
  - codesigning(10)
  - intranet-validation(20)
  - test-unverified(30)
  - ocsp(50)
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

## Information
### certificate-policies(1)
Discription: TrusAuth Certificate Policies (CP) and Certification Practice Statement (CPS)<br>
Information: See [TrusAuth CP and CPS Page](http://www.trusauth.com/repository/)

#### extended-validation(1)
Discription: Extended Validation (EV) <br>
Information: See [TrusAuth CP and CPS Page](http://www.trusauth.com/repository/)

##### SSL(1)
Discription: Secure Sockets Layer (SSL) Extended Validation (EV) policy<br>

##### CodeSigning(2)
Discription: Code signing Extended Validation (EV) policy<br>

#### organization-validation(2)
Discription: Organization Validation (OV) policy<br>
Information: See [TrusAuth CP and CPS Page](http://www.trusauth.com/repository/)

#### domain-validation(3)
Discription: Domain Validation (DV) policy<br>
Information: See [TrusAuth CP and CPS Page](http://www.trusauth.com/repository/)

#### individual-validation(4)
Discription: Individual Validation (IV) policy<br>
Information: See [TrusAuth CP and CPS Page](http://www.trusauth.com/repository/)

#### intranet-validation(20)
Discription: Intranet Validation (INV) policy<br>

#### test-unverified(30)
Discription: Unverified certificate policy<br>

#### ocsp(50)
Discription: Online Certificate Status Procotol (OCSP) policy<br>

### certificate-extensions(2)
Discription: X.509 Certificate Extensions

#### union-verify-list(50)
Discription: TrusAuth Union Verify (UV) List Extension

### certificate-categories(3)

#### id-card-verify(100)
Discription: TrusAuth ID Card Verify (IDCV) Extended Key Usage (EKU)

### union-verify(250)
Discription: TrusAuth Union Verify (UV) Objects