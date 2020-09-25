# Certificate Practice Statement

> Certificate Practice Statement Boilerplate for providing an official CSP for code signing/pki

### Abstract

A CPS is a statement of the practices that a certification authority (CA) employs in issuing, suspending, revoking,
and renewing certificates and providing access to them, in accordance with specific requirements
(i.e., requirements specified in this Certificate Policy, or requirements specified in a contract for services).
<br>
from: [NIST.SP.800-32](https://doi.org/10.6028/NIST.SP.800-32)
<br>

A statement of the practices that a CA employs in issuing, suspending, revoking and renewing certificates and providing access to them,
in accordance with specific requirements (i.e., requirements specified in this CP, or requirements specified in a contract for services).

### Conversion

Originally converted from PDF to Microsoft Docx, then into GitHub Flavoured Markdown and HTML

```bash
# where $filename.docx is the converted PDF from GlobalSign
$ pandoc -f docx -t markdown_mmd $filename.docx --output=OUTPUT.md --atx-headers --wrap=none --toc --extract-media=""
```

### Building

Use the files in `dist/` or the compiled outputs offered in the following formats: <br>

1. `.rst` <br>
2. `.md` <br>
3. `.docx` <br>

### Source(s)

[NIST SP 800-32 under Certification Practice Statement (CPS)](https://doi.org/10.6028/NIST.SP.800-32) <br>
[NIST Glossary](https://csrc.nist.gov/glossary/term/certification_practice_statement) <br>
[GlobalSign CPS Template](https://www.globalsign.com/en/repository/TrustedRoot%20Template%20CPS.pdf) <br>

## License

All Rights are owned by their respective holders <br>
No claim asserted over GlobalSign's boilerplate template. Any code is licesned under the ISC licesne <br>
This is not legal advice nor should it be taken as an authoritative guide on issuance of such polices as it relates to CPS guidelines
