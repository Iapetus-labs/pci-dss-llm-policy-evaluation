# PCI DSS policy generation and cross-audit: supporting material

This repository holds supporting material for an MSc Information Security
dissertation submitted to Royal Holloway, University of London, in September 2026.
The dissertation evaluates how effectively two general-purpose large language models
generate and audit information security policies against PCI DSS v4.0.1.

## What is here

| File | Contents |
|---|---|
| Appendix E, Phase 1 Run Pack and Capture Log | The six policies generated in Phase 1, reproduced verbatim as returned, each with its capture block. Runs P1a, P1b, P2a, P2b, P1c and P2c. |
| Appendix F, Phase 2 Audit Run Pack and Capture Log | The two calibration runs and the four cross-audits, reproduced verbatim as returned, each with its capture block. Audits A(P1a), A(P1b), A(P2a) and A(P2b). |

## How this material was created

The policies and audits were produced by prompting two commercially available large
language models: ChatGPT at build 5.6 Sol and Grok at build 4.5, both through their
consumer applications rather than an API. Each run was executed in a fresh session
with no earlier conversation, no saved history and no custom instructions. No
parameter was changed from its default. Every prompt is reproduced in the
dissertation at Appendix B, and every output here is reproduced exactly as the model
returned it, with no editing, shortening or tidying.

Large language models were the object of study. No large language model was used to
write, structure or format the dissertation itself.

## What is not here, and why

- The PCI DSS v4.0.1 requirement extract, because that text belongs to the PCI
  Security Standards Council and is not the author's to republish.
- The scoring workbook and the twelve completed reviewer response forms, because the
  participant information sheet undertakes that reviewer data is held on University
  systems and is not published.

## Use

All rights reserved. The material is published so that the results reported in the
dissertation can be checked. Please cite the dissertation rather than this repository.
