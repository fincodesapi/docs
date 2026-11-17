# FinCodes API Documentation

This repository contains the source for the FinCodes API documentation, published at **[docs.fincodesapi.com](https://docs.fincodesapi.com)**.

FinCodes API is a REST API for validating and looking up bank codes, verifying payees and screening against sanctions lists. It helps you check payment details before money is sent. The interactive reference (Swagger UI) is at [docs.fincodesapi.com](https://docs.fincodesapi.com).

## Features

### [IBAN Validation](https://fincodesapi.com/iban-number-validation)

Validates an IBAN and returns its country, bank, branch, account and BIC details.

### [BIC Validation](https://fincodesapi.com/bic-code-validation)

Validates a BIC/SWIFT code and returns the bank, branch, country, city, address and postcode.

### [US ABA/RTN Validation](https://fincodesapi.com/us-aba-rtn-number-validation)

Validates a nine-digit ABA routing transit number and identifies the US financial institution.

### [Canada Routing Number Validation](https://fincodesapi.com/canada-routing-number-validation)

Validates an eight-digit Canadian routing number and identifies the institution and branch.

### [Australia BSB Validation](https://fincodesapi.com/bsb-number-validation)

Validates a six-digit BSB number and identifies the Australian bank and branch.

### [New Zealand NCC Validation](https://fincodesapi.com/ncc-code-validation)

Validates a six-digit National Clearing Code and identifies the New Zealand bank and branch.

### [India IFSC Validation](https://fincodesapi.com/ifsc-code-validation)

Validates an eleven-character IFSC code and identifies the Indian bank and branch.

### [Mexico CLABE Validation](https://fincodesapi.com/clabe-number-validation)

Validates an eighteen-digit CLABE, including its control digit, and identifies the Mexican bank.

### [Argentina CBU Validation](https://fincodesapi.com/cbu-number-validation)

Validates a 22-digit CBU, checking both check digits, and identifies the Argentine bank.

### [Verification of Payee](https://fincodesapi.com/verification-of-payee)

Checks that a beneficiary name matches the account holder of a SEPA IBAN before payment. Returns `MATCH`, `CLOSE_MATCH` or `NO_MATCH`, which helps prevent misdirected payments and fraud.

### [Sanctions Screening](https://fincodesapi.com/sanctions-screening)

Screens people, companies, vessels and aircraft against EU, UK, UN, OFAC, Swiss, Australian and Canadian sanctions lists in one call. Fuzzy matching catches typos, transliterations and aliases, and the lists are updated daily.

### [MCP Server](https://fincodesapi.com/mcp-server)

Lets Claude, ChatGPT or VS Code look up IBANs, BIC/SWIFT codes, bank codes, payee names and sanctions in plain language.

See all features at [fincodesapi.com/features](https://fincodesapi.com/features).
