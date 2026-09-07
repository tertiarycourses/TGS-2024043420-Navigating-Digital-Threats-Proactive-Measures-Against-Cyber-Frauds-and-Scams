# Activity 2: Phishing URL and Header Analysis

**Alignment:** LO1 / A1
**Objective:** Inspect a simulated phishing message without opening its link or attachment.

## Safety and scope

Use only the simulated data supplied in this folder. Do not test live suspicious links, accounts, phone numbers or payment routes.

## Procedure

1. Work only from the supplied offline email sample and URL text file.
2. Compare the display name with the From and Reply-To domains.
3. Read Received hops from bottom to top and identify the first untrusted handoff.
4. Check SPF, DKIM and DMARC results recorded in Authentication-Results.
5. Decompose the URL into scheme, host, registrable domain, path and query.
6. Flag punycode, look-alike characters, subdomain deception and redirect parameters.
7. Write an independent verification route using a known bookmark or official directory.
8. Capture the findings in the evidence template and assign a disposition.

## Evidence to submit

Annotated header and URL decomposition with disposition.

## Acceptance check

The registrable domain and authentication result are stated correctly and no live suspect link is opened.

## Reflection

Which observable fact most changed your decision, and which uncertainty remains?
