# Credit card complaint watch

Escrow: `esc_ea0b808575244e5d9a3e43a7`. Buyer: MeridianRisk. Prepared from the official CFPB complaint export.

Status: FINAL — both source pulls completed; platform note timing must also pass before submission.

## Method

Current window: 2026-08-03 through 2026-10-31 inclusive. Prior window: 2026-05-05 through 2026-08-02 inclusive. Both requests filter product=Credit card and format=csv. Each CSV response is read in full; the header is excluded from row counts. Each Complaint ID is nonempty and unique within its source file. No company exclusions, spelling normalization, merging, or deduplication were applied.

The 20-company cohort is ranked by current pull 1 count, descending, with exact Company string ascending to break ties. That cohort is held fixed in pull 2 so the change check measures complaint-record changes. Tables (a)–(c) use pull 1 current and prior sources; the second-pull section records updates. Missing cells stay empty. Literal source text such as "None" remains literal text. Export date/timestamp strings are preserved exactly. Percent change = 100 × (current − prior) / prior, rounded to two decimals; it is undefined when prior = 0. Each reported issue is the exact Issue string. Zero/zero pairs are included in table (b). Largest-contributor ties are resolved by exact company string ascending.

## (a) Top 20 companies

| Rank | Company (exact string) | Current | Prior | Change | Percent change |
| --- | --- | --- | --- | --- | --- |
| 1 | CAPITAL ONE FINANCIAL CORPORATION | 3769 | 3606 | 163 | 4.52% |
| 2 | CITIBANK, N.A. | 3136 | 3135 | 1 | 0.03% |
| 3 | SYNCHRONY FINANCIAL | 2380 | 2214 | 166 | 7.50% |
| 4 | JPMORGAN CHASE & CO. | 1839 | 1721 | 118 | 6.86% |
| 5 | BANK OF AMERICA, NATIONAL ASSOCIATION | 1555 | 1568 | -13 | -0.83% |
| 6 | AMERICAN EXPRESS COMPANY | 1457 | 1451 | 6 | 0.41% |
| 7 | WELLS FARGO & COMPANY | 799 | 890 | -91 | -10.22% |
| 8 | Bread Financial Holdings, Inc. | 776 | 864 | -88 | -10.19% |
| 9 | GOLDMAN SACHS BANK USA | 740 | 688 | 52 | 7.56% |
| 10 | BARCLAYS BANK DELAWARE | 716 | 690 | 26 | 3.77% |
| 11 | U.S. BANCORP | 517 | 498 | 19 | 3.82% |
| 12 | TRANSUNION INTERMEDIATE HOLDINGS, INC. | 378 | 355 | 23 | 6.48% |
| 13 | Experian Information Solutions Inc. | 377 | 337 | 40 | 11.87% |
| 14 | Chime Financial Inc | 321 | 312 | 9 | 2.88% |
| 15 | NAVY FEDERAL CREDIT UNION | 309 | 274 | 35 | 12.77% |
| 16 | TD BANK US HOLDING COMPANY | 295 | 364 | -69 | -18.96% |
| 17 | EQUIFAX, INC. | 269 | 278 | -9 | -3.24% |
| 18 | CLGF Holdco 1, LLC | 264 | 283 | -19 | -6.71% |
| 19 | ROBINHOOD MARKETS INC. | 199 | 176 | 23 | 13.07% |
| 20 | Atlanticus Services Corporation | 194 | 208 | -14 | -6.73% |

Table (a) current total: 20290 = pull 1 attached CSV data rows: 20290.

## (b) Every company by issue

| Company (exact string) | Issue (exact string) | Current | Prior | Change |
| --- | --- | --- | --- | --- |
| CAPITAL ONE FINANCIAL CORPORATION | Advertising and marketing, including promotional offers | 173 | 168 | 5 |
| CAPITAL ONE FINANCIAL CORPORATION | Closing your account | 350 | 329 | 21 |
| CAPITAL ONE FINANCIAL CORPORATION | Credit monitoring or identity theft protection services | 7 | 9 | -2 |
| CAPITAL ONE FINANCIAL CORPORATION | Fees or interest | 309 | 261 | 48 |
| CAPITAL ONE FINANCIAL CORPORATION | Getting a credit card | 337 | 353 | -16 |
| CAPITAL ONE FINANCIAL CORPORATION | Improper use of your report | 13 | 28 | -15 |
| CAPITAL ONE FINANCIAL CORPORATION | Incorrect information on your report | 199 | 230 | -31 |
| CAPITAL ONE FINANCIAL CORPORATION | Other features, terms, or problems | 554 | 467 | 87 |
| CAPITAL ONE FINANCIAL CORPORATION | Problem when making payments | 161 | 150 | 11 |
| CAPITAL ONE FINANCIAL CORPORATION | Problem with a company's investigation into an existing problem | 95 | 137 | -42 |
| CAPITAL ONE FINANCIAL CORPORATION | Problem with a purchase shown on your statement | 1264 | 1219 | 45 |
| CAPITAL ONE FINANCIAL CORPORATION | Problem with fraud alerts or security freezes | 2 | 3 | -1 |
| CAPITAL ONE FINANCIAL CORPORATION | Struggling to pay your bill | 89 | 51 | 38 |
| CAPITAL ONE FINANCIAL CORPORATION | Trouble using your card | 213 | 200 | 13 |
| CAPITAL ONE FINANCIAL CORPORATION | Unable to get your credit report or credit score | 3 | 1 | 2 |
| CITIBANK, N.A. | Advertising and marketing, including promotional offers | 190 | 154 | 36 |
| CITIBANK, N.A. | Closing your account | 194 | 233 | -39 |
| CITIBANK, N.A. | Credit monitoring or identity theft protection services | 1 | 7 | -6 |
| CITIBANK, N.A. | Fees or interest | 380 | 375 | 5 |
| CITIBANK, N.A. | Getting a credit card | 266 | 240 | 26 |
| CITIBANK, N.A. | Improper use of your report | 16 | 13 | 3 |
| CITIBANK, N.A. | Incorrect information on your report | 80 | 84 | -4 |
| CITIBANK, N.A. | Other features, terms, or problems | 407 | 401 | 6 |
| CITIBANK, N.A. | Problem when making payments | 165 | 188 | -23 |
| CITIBANK, N.A. | Problem with a company's investigation into an existing problem | 63 | 57 | 6 |
| CITIBANK, N.A. | Problem with a purchase shown on your statement | 1196 | 1200 | -4 |
| CITIBANK, N.A. | Problem with fraud alerts or security freezes | 1 | 4 | -3 |
| CITIBANK, N.A. | Struggling to pay your bill | 22 | 18 | 4 |
| CITIBANK, N.A. | Trouble using your card | 155 | 161 | -6 |
| CITIBANK, N.A. | Unable to get your credit report or credit score | 0 | 0 | 0 |
| SYNCHRONY FINANCIAL | Advertising and marketing, including promotional offers | 165 | 148 | 17 |
| SYNCHRONY FINANCIAL | Closing your account | 225 | 216 | 9 |
| SYNCHRONY FINANCIAL | Credit monitoring or identity theft protection services | 2 | 4 | -2 |
| SYNCHRONY FINANCIAL | Fees or interest | 523 | 499 | 24 |
| SYNCHRONY FINANCIAL | Getting a credit card | 143 | 163 | -20 |
| SYNCHRONY FINANCIAL | Improper use of your report | 12 | 6 | 6 |
| SYNCHRONY FINANCIAL | Incorrect information on your report | 65 | 70 | -5 |
| SYNCHRONY FINANCIAL | Other features, terms, or problems | 231 | 179 | 52 |
| SYNCHRONY FINANCIAL | Problem when making payments | 174 | 148 | 26 |
| SYNCHRONY FINANCIAL | Problem with a company's investigation into an existing problem | 28 | 43 | -15 |
| SYNCHRONY FINANCIAL | Problem with a purchase shown on your statement | 688 | 620 | 68 |
| SYNCHRONY FINANCIAL | Problem with fraud alerts or security freezes | 2 | 2 | 0 |
| SYNCHRONY FINANCIAL | Struggling to pay your bill | 22 | 16 | 6 |
| SYNCHRONY FINANCIAL | Trouble using your card | 98 | 99 | -1 |
| SYNCHRONY FINANCIAL | Unable to get your credit report or credit score | 2 | 1 | 1 |
| JPMORGAN CHASE & CO. | Advertising and marketing, including promotional offers | 188 | 148 | 40 |
| JPMORGAN CHASE & CO. | Closing your account | 109 | 98 | 11 |
| JPMORGAN CHASE & CO. | Credit monitoring or identity theft protection services | 3 | 1 | 2 |
| JPMORGAN CHASE & CO. | Fees or interest | 133 | 109 | 24 |
| JPMORGAN CHASE & CO. | Getting a credit card | 137 | 149 | -12 |
| JPMORGAN CHASE & CO. | Improper use of your report | 13 | 12 | 1 |
| JPMORGAN CHASE & CO. | Incorrect information on your report | 67 | 75 | -8 |
| JPMORGAN CHASE & CO. | Other features, terms, or problems | 386 | 365 | 21 |
| JPMORGAN CHASE & CO. | Problem when making payments | 53 | 62 | -9 |
| JPMORGAN CHASE & CO. | Problem with a company's investigation into an existing problem | 33 | 45 | -12 |
| JPMORGAN CHASE & CO. | Problem with a purchase shown on your statement | 628 | 561 | 67 |
| JPMORGAN CHASE & CO. | Problem with fraud alerts or security freezes | 0 | 0 | 0 |
| JPMORGAN CHASE & CO. | Struggling to pay your bill | 27 | 31 | -4 |
| JPMORGAN CHASE & CO. | Trouble using your card | 61 | 64 | -3 |
| JPMORGAN CHASE & CO. | Unable to get your credit report or credit score | 1 | 1 | 0 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Advertising and marketing, including promotional offers | 30 | 27 | 3 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Closing your account | 100 | 82 | 18 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Credit monitoring or identity theft protection services | 1 | 4 | -3 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Fees or interest | 112 | 116 | -4 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Getting a credit card | 98 | 90 | 8 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Improper use of your report | 1 | 0 | 1 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Incorrect information on your report | 89 | 76 | 13 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Other features, terms, or problems | 197 | 165 | 32 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Problem when making payments | 96 | 104 | -8 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Problem with a company's investigation into an existing problem | 66 | 63 | 3 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Problem with a purchase shown on your statement | 702 | 779 | -77 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Struggling to pay your bill | 20 | 21 | -1 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Trouble using your card | 42 | 40 | 2 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | Unable to get your credit report or credit score | 1 | 0 | 1 |
| AMERICAN EXPRESS COMPANY | Advertising and marketing, including promotional offers | 150 | 149 | 1 |
| AMERICAN EXPRESS COMPANY | Closing your account | 96 | 88 | 8 |
| AMERICAN EXPRESS COMPANY | Credit monitoring or identity theft protection services | 2 | 0 | 2 |
| AMERICAN EXPRESS COMPANY | Fees or interest | 136 | 142 | -6 |
| AMERICAN EXPRESS COMPANY | Getting a credit card | 122 | 75 | 47 |
| AMERICAN EXPRESS COMPANY | Improper use of your report | 2 | 1 | 1 |
| AMERICAN EXPRESS COMPANY | Incorrect information on your report | 46 | 54 | -8 |
| AMERICAN EXPRESS COMPANY | Other features, terms, or problems | 227 | 260 | -33 |
| AMERICAN EXPRESS COMPANY | Problem when making payments | 39 | 48 | -9 |
| AMERICAN EXPRESS COMPANY | Problem with a company's investigation into an existing problem | 29 | 41 | -12 |
| AMERICAN EXPRESS COMPANY | Problem with a purchase shown on your statement | 513 | 518 | -5 |
| AMERICAN EXPRESS COMPANY | Problem with fraud alerts or security freezes | 0 | 0 | 0 |
| AMERICAN EXPRESS COMPANY | Struggling to pay your bill | 26 | 7 | 19 |
| AMERICAN EXPRESS COMPANY | Trouble using your card | 69 | 68 | 1 |
| AMERICAN EXPRESS COMPANY | Unable to get your credit report or credit score | 0 | 0 | 0 |
| WELLS FARGO & COMPANY | Advertising and marketing, including promotional offers | 27 | 38 | -11 |
| WELLS FARGO & COMPANY | Closing your account | 37 | 47 | -10 |
| WELLS FARGO & COMPANY | Credit monitoring or identity theft protection services | 1 | 1 | 0 |
| WELLS FARGO & COMPANY | Fees or interest | 79 | 72 | 7 |
| WELLS FARGO & COMPANY | Getting a credit card | 68 | 109 | -41 |
| WELLS FARGO & COMPANY | Improper use of your report | 4 | 7 | -3 |
| WELLS FARGO & COMPANY | Incorrect information on your report | 35 | 38 | -3 |
| WELLS FARGO & COMPANY | Other features, terms, or problems | 133 | 124 | 9 |
| WELLS FARGO & COMPANY | Problem when making payments | 43 | 52 | -9 |
| WELLS FARGO & COMPANY | Problem with a company's investigation into an existing problem | 18 | 26 | -8 |
| WELLS FARGO & COMPANY | Problem with a purchase shown on your statement | 288 | 341 | -53 |
| WELLS FARGO & COMPANY | Problem with fraud alerts or security freezes | 1 | 1 | 0 |
| WELLS FARGO & COMPANY | Struggling to pay your bill | 20 | 9 | 11 |
| WELLS FARGO & COMPANY | Trouble using your card | 45 | 24 | 21 |
| WELLS FARGO & COMPANY | Unable to get your credit report or credit score | 0 | 1 | -1 |
| Bread Financial Holdings, Inc. | Advertising and marketing, including promotional offers | 49 | 59 | -10 |
| Bread Financial Holdings, Inc. | Closing your account | 32 | 51 | -19 |
| Bread Financial Holdings, Inc. | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| Bread Financial Holdings, Inc. | Fees or interest | 259 | 278 | -19 |
| Bread Financial Holdings, Inc. | Getting a credit card | 68 | 72 | -4 |
| Bread Financial Holdings, Inc. | Improper use of your report | 4 | 4 | 0 |
| Bread Financial Holdings, Inc. | Incorrect information on your report | 54 | 67 | -13 |
| Bread Financial Holdings, Inc. | Other features, terms, or problems | 56 | 64 | -8 |
| Bread Financial Holdings, Inc. | Problem when making payments | 55 | 54 | 1 |
| Bread Financial Holdings, Inc. | Problem with a company's investigation into an existing problem | 31 | 34 | -3 |
| Bread Financial Holdings, Inc. | Problem with a purchase shown on your statement | 128 | 131 | -3 |
| Bread Financial Holdings, Inc. | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| Bread Financial Holdings, Inc. | Struggling to pay your bill | 14 | 20 | -6 |
| Bread Financial Holdings, Inc. | Trouble using your card | 26 | 27 | -1 |
| Bread Financial Holdings, Inc. | Unable to get your credit report or credit score | 0 | 1 | -1 |
| GOLDMAN SACHS BANK USA | Advertising and marketing, including promotional offers | 4 | 6 | -2 |
| GOLDMAN SACHS BANK USA | Closing your account | 19 | 27 | -8 |
| GOLDMAN SACHS BANK USA | Credit monitoring or identity theft protection services | 1 | 1 | 0 |
| GOLDMAN SACHS BANK USA | Fees or interest | 14 | 14 | 0 |
| GOLDMAN SACHS BANK USA | Getting a credit card | 37 | 36 | 1 |
| GOLDMAN SACHS BANK USA | Improper use of your report | 2 | 1 | 1 |
| GOLDMAN SACHS BANK USA | Incorrect information on your report | 25 | 29 | -4 |
| GOLDMAN SACHS BANK USA | Other features, terms, or problems | 36 | 29 | 7 |
| GOLDMAN SACHS BANK USA | Problem when making payments | 19 | 34 | -15 |
| GOLDMAN SACHS BANK USA | Problem with a company's investigation into an existing problem | 19 | 26 | -7 |
| GOLDMAN SACHS BANK USA | Problem with a purchase shown on your statement | 514 | 448 | 66 |
| GOLDMAN SACHS BANK USA | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| GOLDMAN SACHS BANK USA | Struggling to pay your bill | 22 | 15 | 7 |
| GOLDMAN SACHS BANK USA | Trouble using your card | 28 | 21 | 7 |
| GOLDMAN SACHS BANK USA | Unable to get your credit report or credit score | 0 | 0 | 0 |
| BARCLAYS BANK DELAWARE | Advertising and marketing, including promotional offers | 38 | 33 | 5 |
| BARCLAYS BANK DELAWARE | Closing your account | 31 | 32 | -1 |
| BARCLAYS BANK DELAWARE | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| BARCLAYS BANK DELAWARE | Fees or interest | 46 | 31 | 15 |
| BARCLAYS BANK DELAWARE | Getting a credit card | 96 | 86 | 10 |
| BARCLAYS BANK DELAWARE | Improper use of your report | 4 | 5 | -1 |
| BARCLAYS BANK DELAWARE | Incorrect information on your report | 34 | 42 | -8 |
| BARCLAYS BANK DELAWARE | Other features, terms, or problems | 86 | 96 | -10 |
| BARCLAYS BANK DELAWARE | Problem when making payments | 35 | 29 | 6 |
| BARCLAYS BANK DELAWARE | Problem with a company's investigation into an existing problem | 28 | 26 | 2 |
| BARCLAYS BANK DELAWARE | Problem with a purchase shown on your statement | 256 | 265 | -9 |
| BARCLAYS BANK DELAWARE | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| BARCLAYS BANK DELAWARE | Struggling to pay your bill | 15 | 6 | 9 |
| BARCLAYS BANK DELAWARE | Trouble using your card | 47 | 37 | 10 |
| BARCLAYS BANK DELAWARE | Unable to get your credit report or credit score | 0 | 0 | 0 |
| U.S. BANCORP | Advertising and marketing, including promotional offers | 19 | 26 | -7 |
| U.S. BANCORP | Closing your account | 60 | 47 | 13 |
| U.S. BANCORP | Credit monitoring or identity theft protection services | 0 | 0 | 0 |
| U.S. BANCORP | Fees or interest | 54 | 65 | -11 |
| U.S. BANCORP | Getting a credit card | 34 | 46 | -12 |
| U.S. BANCORP | Improper use of your report | 2 | 2 | 0 |
| U.S. BANCORP | Incorrect information on your report | 12 | 19 | -7 |
| U.S. BANCORP | Other features, terms, or problems | 104 | 93 | 11 |
| U.S. BANCORP | Problem when making payments | 28 | 27 | 1 |
| U.S. BANCORP | Problem with a company's investigation into an existing problem | 7 | 3 | 4 |
| U.S. BANCORP | Problem with a purchase shown on your statement | 163 | 141 | 22 |
| U.S. BANCORP | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| U.S. BANCORP | Struggling to pay your bill | 4 | 6 | -2 |
| U.S. BANCORP | Trouble using your card | 30 | 22 | 8 |
| U.S. BANCORP | Unable to get your credit report or credit score | 0 | 0 | 0 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Advertising and marketing, including promotional offers | 1 | 3 | -2 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Closing your account | 4 | 4 | 0 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Fees or interest | 2 | 2 | 0 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Getting a credit card | 324 | 219 | 105 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Improper use of your report | 3 | 6 | -3 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Incorrect information on your report | 25 | 39 | -14 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Other features, terms, or problems | 7 | 1 | 6 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Problem when making payments | 0 | 4 | -4 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Problem with a company's investigation into an existing problem | 4 | 73 | -69 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Problem with a purchase shown on your statement | 4 | 2 | 2 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Problem with fraud alerts or security freezes | 2 | 1 | 1 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Struggling to pay your bill | 2 | 0 | 2 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Trouble using your card | 0 | 0 | 0 |
| TRANSUNION INTERMEDIATE HOLDINGS, INC. | Unable to get your credit report or credit score | 0 | 0 | 0 |
| Experian Information Solutions Inc. | Advertising and marketing, including promotional offers | 3 | 1 | 2 |
| Experian Information Solutions Inc. | Closing your account | 6 | 3 | 3 |
| Experian Information Solutions Inc. | Credit monitoring or identity theft protection services | 1 | 3 | -2 |
| Experian Information Solutions Inc. | Fees or interest | 3 | 2 | 1 |
| Experian Information Solutions Inc. | Getting a credit card | 307 | 244 | 63 |
| Experian Information Solutions Inc. | Improper use of your report | 3 | 5 | -2 |
| Experian Information Solutions Inc. | Incorrect information on your report | 27 | 31 | -4 |
| Experian Information Solutions Inc. | Other features, terms, or problems | 4 | 3 | 1 |
| Experian Information Solutions Inc. | Problem when making payments | 1 | 4 | -3 |
| Experian Information Solutions Inc. | Problem with a company's investigation into an existing problem | 7 | 32 | -25 |
| Experian Information Solutions Inc. | Problem with a purchase shown on your statement | 13 | 6 | 7 |
| Experian Information Solutions Inc. | Problem with fraud alerts or security freezes | 1 | 1 | 0 |
| Experian Information Solutions Inc. | Struggling to pay your bill | 0 | 1 | -1 |
| Experian Information Solutions Inc. | Trouble using your card | 1 | 0 | 1 |
| Experian Information Solutions Inc. | Unable to get your credit report or credit score | 0 | 1 | -1 |
| Chime Financial Inc | Advertising and marketing, including promotional offers | 6 | 6 | 0 |
| Chime Financial Inc | Closing your account | 29 | 13 | 16 |
| Chime Financial Inc | Credit monitoring or identity theft protection services | 2 | 1 | 1 |
| Chime Financial Inc | Fees or interest | 1 | 1 | 0 |
| Chime Financial Inc | Getting a credit card | 32 | 28 | 4 |
| Chime Financial Inc | Improper use of your report | 1 | 0 | 1 |
| Chime Financial Inc | Incorrect information on your report | 6 | 10 | -4 |
| Chime Financial Inc | Other features, terms, or problems | 19 | 23 | -4 |
| Chime Financial Inc | Problem when making payments | 5 | 1 | 4 |
| Chime Financial Inc | Problem with a company's investigation into an existing problem | 5 | 3 | 2 |
| Chime Financial Inc | Problem with a purchase shown on your statement | 212 | 226 | -14 |
| Chime Financial Inc | Problem with fraud alerts or security freezes | 0 | 0 | 0 |
| Chime Financial Inc | Struggling to pay your bill | 0 | 0 | 0 |
| Chime Financial Inc | Trouble using your card | 3 | 0 | 3 |
| Chime Financial Inc | Unable to get your credit report or credit score | 0 | 0 | 0 |
| NAVY FEDERAL CREDIT UNION | Advertising and marketing, including promotional offers | 3 | 4 | -1 |
| NAVY FEDERAL CREDIT UNION | Closing your account | 13 | 18 | -5 |
| NAVY FEDERAL CREDIT UNION | Credit monitoring or identity theft protection services | 1 | 0 | 1 |
| NAVY FEDERAL CREDIT UNION | Fees or interest | 22 | 17 | 5 |
| NAVY FEDERAL CREDIT UNION | Getting a credit card | 20 | 30 | -10 |
| NAVY FEDERAL CREDIT UNION | Improper use of your report | 2 | 0 | 2 |
| NAVY FEDERAL CREDIT UNION | Incorrect information on your report | 21 | 27 | -6 |
| NAVY FEDERAL CREDIT UNION | Other features, terms, or problems | 35 | 36 | -1 |
| NAVY FEDERAL CREDIT UNION | Problem when making payments | 8 | 6 | 2 |
| NAVY FEDERAL CREDIT UNION | Problem with a company's investigation into an existing problem | 6 | 14 | -8 |
| NAVY FEDERAL CREDIT UNION | Problem with a purchase shown on your statement | 166 | 110 | 56 |
| NAVY FEDERAL CREDIT UNION | Problem with fraud alerts or security freezes | 1 | 1 | 0 |
| NAVY FEDERAL CREDIT UNION | Struggling to pay your bill | 7 | 9 | -2 |
| NAVY FEDERAL CREDIT UNION | Trouble using your card | 3 | 2 | 1 |
| NAVY FEDERAL CREDIT UNION | Unable to get your credit report or credit score | 1 | 0 | 1 |
| TD BANK US HOLDING COMPANY | Advertising and marketing, including promotional offers | 10 | 12 | -2 |
| TD BANK US HOLDING COMPANY | Closing your account | 20 | 16 | 4 |
| TD BANK US HOLDING COMPANY | Credit monitoring or identity theft protection services | 1 | 1 | 0 |
| TD BANK US HOLDING COMPANY | Fees or interest | 37 | 33 | 4 |
| TD BANK US HOLDING COMPANY | Getting a credit card | 35 | 26 | 9 |
| TD BANK US HOLDING COMPANY | Improper use of your report | 1 | 2 | -1 |
| TD BANK US HOLDING COMPANY | Incorrect information on your report | 23 | 40 | -17 |
| TD BANK US HOLDING COMPANY | Other features, terms, or problems | 23 | 43 | -20 |
| TD BANK US HOLDING COMPANY | Problem when making payments | 33 | 37 | -4 |
| TD BANK US HOLDING COMPANY | Problem with a company's investigation into an existing problem | 16 | 31 | -15 |
| TD BANK US HOLDING COMPANY | Problem with a purchase shown on your statement | 64 | 99 | -35 |
| TD BANK US HOLDING COMPANY | Problem with fraud alerts or security freezes | 1 | 0 | 1 |
| TD BANK US HOLDING COMPANY | Struggling to pay your bill | 10 | 8 | 2 |
| TD BANK US HOLDING COMPANY | Trouble using your card | 21 | 15 | 6 |
| TD BANK US HOLDING COMPANY | Unable to get your credit report or credit score | 0 | 1 | -1 |
| EQUIFAX, INC. | Advertising and marketing, including promotional offers | 2 | 6 | -4 |
| EQUIFAX, INC. | Closing your account | 3 | 1 | 2 |
| EQUIFAX, INC. | Credit monitoring or identity theft protection services | 1 | 1 | 0 |
| EQUIFAX, INC. | Fees or interest | 2 | 2 | 0 |
| EQUIFAX, INC. | Getting a credit card | 213 | 194 | 19 |
| EQUIFAX, INC. | Improper use of your report | 1 | 6 | -5 |
| EQUIFAX, INC. | Incorrect information on your report | 26 | 34 | -8 |
| EQUIFAX, INC. | Other features, terms, or problems | 12 | 4 | 8 |
| EQUIFAX, INC. | Problem when making payments | 1 | 1 | 0 |
| EQUIFAX, INC. | Problem with a company's investigation into an existing problem | 3 | 26 | -23 |
| EQUIFAX, INC. | Problem with a purchase shown on your statement | 3 | 3 | 0 |
| EQUIFAX, INC. | Problem with fraud alerts or security freezes | 1 | 0 | 1 |
| EQUIFAX, INC. | Struggling to pay your bill | 1 | 0 | 1 |
| EQUIFAX, INC. | Trouble using your card | 0 | 0 | 0 |
| EQUIFAX, INC. | Unable to get your credit report or credit score | 0 | 0 | 0 |
| CLGF Holdco 1, LLC | Advertising and marketing, including promotional offers | 12 | 9 | 3 |
| CLGF Holdco 1, LLC | Closing your account | 30 | 23 | 7 |
| CLGF Holdco 1, LLC | Credit monitoring or identity theft protection services | 1 | 0 | 1 |
| CLGF Holdco 1, LLC | Fees or interest | 58 | 81 | -23 |
| CLGF Holdco 1, LLC | Getting a credit card | 35 | 39 | -4 |
| CLGF Holdco 1, LLC | Improper use of your report | 0 | 2 | -2 |
| CLGF Holdco 1, LLC | Incorrect information on your report | 4 | 10 | -6 |
| CLGF Holdco 1, LLC | Other features, terms, or problems | 26 | 26 | 0 |
| CLGF Holdco 1, LLC | Problem when making payments | 24 | 16 | 8 |
| CLGF Holdco 1, LLC | Problem with a company's investigation into an existing problem | 5 | 8 | -3 |
| CLGF Holdco 1, LLC | Problem with a purchase shown on your statement | 41 | 33 | 8 |
| CLGF Holdco 1, LLC | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| CLGF Holdco 1, LLC | Struggling to pay your bill | 13 | 20 | -7 |
| CLGF Holdco 1, LLC | Trouble using your card | 15 | 15 | 0 |
| CLGF Holdco 1, LLC | Unable to get your credit report or credit score | 0 | 0 | 0 |
| ROBINHOOD MARKETS INC. | Advertising and marketing, including promotional offers | 10 | 4 | 6 |
| ROBINHOOD MARKETS INC. | Closing your account | 6 | 5 | 1 |
| ROBINHOOD MARKETS INC. | Credit monitoring or identity theft protection services | 0 | 0 | 0 |
| ROBINHOOD MARKETS INC. | Fees or interest | 13 | 12 | 1 |
| ROBINHOOD MARKETS INC. | Getting a credit card | 8 | 20 | -12 |
| ROBINHOOD MARKETS INC. | Improper use of your report | 0 | 0 | 0 |
| ROBINHOOD MARKETS INC. | Incorrect information on your report | 1 | 1 | 0 |
| ROBINHOOD MARKETS INC. | Other features, terms, or problems | 17 | 24 | -7 |
| ROBINHOOD MARKETS INC. | Problem when making payments | 6 | 3 | 3 |
| ROBINHOOD MARKETS INC. | Problem with a company's investigation into an existing problem | 0 | 2 | -2 |
| ROBINHOOD MARKETS INC. | Problem with a purchase shown on your statement | 135 | 91 | 44 |
| ROBINHOOD MARKETS INC. | Problem with fraud alerts or security freezes | 0 | 0 | 0 |
| ROBINHOOD MARKETS INC. | Struggling to pay your bill | 2 | 1 | 1 |
| ROBINHOOD MARKETS INC. | Trouble using your card | 1 | 13 | -12 |
| ROBINHOOD MARKETS INC. | Unable to get your credit report or credit score | 0 | 0 | 0 |
| Atlanticus Services Corporation | Advertising and marketing, including promotional offers | 6 | 6 | 0 |
| Atlanticus Services Corporation | Closing your account | 19 | 22 | -3 |
| Atlanticus Services Corporation | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| Atlanticus Services Corporation | Fees or interest | 45 | 54 | -9 |
| Atlanticus Services Corporation | Getting a credit card | 38 | 35 | 3 |
| Atlanticus Services Corporation | Improper use of your report | 1 | 0 | 1 |
| Atlanticus Services Corporation | Incorrect information on your report | 7 | 9 | -2 |
| Atlanticus Services Corporation | Other features, terms, or problems | 19 | 17 | 2 |
| Atlanticus Services Corporation | Problem when making payments | 13 | 10 | 3 |
| Atlanticus Services Corporation | Problem with a company's investigation into an existing problem | 2 | 3 | -1 |
| Atlanticus Services Corporation | Problem with a purchase shown on your statement | 32 | 41 | -9 |
| Atlanticus Services Corporation | Problem with fraud alerts or security freezes | 0 | 0 | 0 |
| Atlanticus Services Corporation | Struggling to pay your bill | 11 | 4 | 7 |
| Atlanticus Services Corporation | Trouble using your card | 1 | 6 | -5 |
| Atlanticus Services Corporation | Unable to get your credit report or credit score | 0 | 0 | 0 |

## (c) Ten issues ranked by increase

| Issue | Current | Prior | Increase | Largest-contributing company | Company increase |
| --- | --- | --- | --- | --- | --- |
| Problem with a purchase shown on your statement | 7010 | 6834 | 176 | SYNCHRONY FINANCIAL | 68 |
| Getting a credit card | 2418 | 2254 | 164 | TRANSUNION INTERMEDIATE HOLDINGS, INC. | 105 |
| Other features, terms, or problems | 2579 | 2420 | 159 | CAPITAL ONE FINANCIAL CORPORATION | 87 |
| Struggling to pay your bill | 327 | 243 | 84 | CAPITAL ONE FINANCIAL CORPORATION | 38 |
| Advertising and marketing, including promotional offers | 1086 | 1007 | 79 | JPMORGAN CHASE & CO. | 40 |
| Fees or interest | 2228 | 2166 | 62 | CAPITAL ONE FINANCIAL CORPORATION | 48 |
| Trouble using your card | 859 | 814 | 45 | WELLS FARGO & COMPANY | 21 |
| Closing your account | 1383 | 1355 | 28 | CAPITAL ONE FINANCIAL CORPORATION | 21 |
| Unable to get your credit report or credit score | 8 | 7 | 1 | CAPITAL ONE FINANCIAL CORPORATION | 2 |
| Problem with fraud alerts or security freezes | 12 | 19 | -7 | EQUIFAX, INC. | 1 |

## Full source row-count reconciliation

| Pull | Window | Actual full rows | Expected rows | Difference | Retrieved UTC |
| --- | --- | --- | --- | --- | --- |
| 1 | current | 22786 | 22786 | 0 | 2026-11-02T00:31:47.422Z |
| 1 | prior | 22835 | 22835 | 0 | 2026-11-02T00:31:50.004Z |
| 2 | current | 22793 | 22786 | 7 | 2026-11-03T05:28:34.316Z |
| 2 | prior | 22835 | 22835 | 0 | 2026-11-03T05:28:39.813Z |

## Attached CSV files

- `ccdb-top20-pull1.csv`: 20290 data rows; 6257823 bytes; SHA-256 `c019257d422285e2b1a21230903c8eecf801817875f596d6756d7b8bd42ef1dd`.
- `ccdb-top20-pull2.csv`: 20293 data rows; 6259820 bytes; SHA-256 `4afd80ac9c6cb918489f7052e248dcef4a48fe1581c632937bd452b263a4982b`.

```synmerco-data
c019257d422285e2b1a21230903c8eecf801817875f596d6756d7b8bd42ef1dd ccdb-top20-pull1.csv
4afd80ac9c6cb918489f7052e248dcef4a48fe1581c632937bd452b263a4982b ccdb-top20-pull2.csv
```

## Changes between the attached CSV files

| Pull 1 rows | Pull 2 rows | New keys | Gone keys | Changed keys | Changed cells |
| --- | --- | --- | --- | --- | --- |
| 20290 | 20293 | 3 | 0 | 19 | 30 |

Row invariant: 20293 = 20290 + 3 − 0. All 14 non-key columns were compared as exact strings.

| Complaint ID | Column | Pull 1 value | Pull 2 value |
| --- | --- | --- | --- |
| 26328311 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 26328311 | Company response to consumer | In progress | Closed with explanation |
| 26344642 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 26344642 | Company response to consumer | In progress | Closed with explanation |
| 26353611 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 26353611 | Company response to consumer | In progress | Closed with explanation |
| 26358332 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 26358332 | Company response to consumer | In progress | Closed with explanation |
| 26361404 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 26361404 | Company response to consumer | In progress | Closed with explanation |
| 26413478 | Company response to consumer | In progress | Closed with explanation |
| 26637032 | Company response to consumer | In progress | Closed with explanation |
| 27117863 | Company response to consumer | In progress | Closed with explanation |
| 27128172 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 27128172 | Company response to consumer | In progress | Closed with explanation |
| 27331980 | Company response to consumer | In progress | Closed with explanation |
| 27514359 | Company response to consumer | In progress | Closed with explanation |
| 27556120 | Company response to consumer | In progress | Closed with non-monetary relief |
| 27652805 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 27652805 | Company response to consumer | In progress | Closed with explanation |
| 28391021 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 28391021 | Company response to consumer | In progress | Closed with non-monetary relief |
| 28423532 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 28423532 | Company response to consumer | In progress | Closed with non-monetary relief |
| 28449802 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 28449802 | Company response to consumer | In progress | Closed with explanation |
| 28449853 | Company public response | None | Company has responded to the consumer and the CFPB and chooses not to provide a public response |
| 28449853 | Company response to consumer | In progress | Closed with explanation |
| 29776372 | Company response to consumer | In progress | Closed with monetary relief |
| 29986187 | Company response to consumer | In progress | Closed with explanation |

New Complaint IDs: 30309373, 30353604, 30662561

## Platform progress record

- Platform recordedAt: `2026-11-02 00:31:58.942065+00`. Note: PULL 1: ccdb-top20-pull1.csv; 20290 data rows (header excluded); SHA-256 c019257d422285e2b1a21230903c8eecf801817875f596d6756d7b8bd42ef1dd. Current source retrieved 2026-11-02T00:31:47.422Z; prior source retrieved 2026-11-02T00:31:50.004Z. Full current 22786 rows (expected 22786; difference 0); full prior 22835 rows (expected 22835; difference 0). The fixed cohort contains the top 20 exact Company strings from pull 1. Second pull will start at least 24 hours after this platform-stamped note.
- Platform recordedAt: `2026-11-02 00:34:02.016097+00`. Note: WAITING: Pull 1 is complete. Synmerco verified ccdb-top20-pull1.csv (20,290 rows, SHA-256 c019257d422285e2b1a21230903c8eecf801817875f596d6756d7b8bd42ef1dd). Tables (a)-(c) have been prepared and reconciled against the full sources and the attached file. I am waiting for the required 24-hour interval after the platform PULL 1 note at 2026-11-02T00:31:58.942065Z. Pull 2 will begin no earlier than 2026-11-03T00:32:08.942065Z, then both source requests will be repeated and every non-key column compared by Complaint ID before final delivery.
- Platform recordedAt: `2026-11-03 05:28:42.395285+00`. Note: PULL 2: ccdb-top20-pull2.csv; 20293 data rows (header excluded); SHA-256 4afd80ac9c6cb918489f7052e248dcef4a48fe1581c632937bd452b263a4982b. Current source retrieved 2026-11-03T05:28:34.316Z; prior source retrieved 2026-11-03T05:28:39.813Z. Full current 22793 rows (expected 22786; difference 7); full prior 22835 rows (expected 22835; difference 0). The fixed cohort contains the top 20 exact Company strings from pull 1. All non-key columns are compared by Complaint ID in the final report.

## Source proof

Each excerpt below reproduces the response headers in received order followed by the CSV header and the first three source rows. The local retrieval timestamp and the source Date header are distinct. Raw CSV files and HTTP header dumps are retained locally; attachments are the fixed 20-company subset.

### Pull 1, current, attempt 1

Request: GET https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1/?format=csv&date_received_min=2026-08-03&date_received_max=2026-10-31&product=Credit%20card
Host: `www.consumerfinance.gov`. Endpoint: `/data-research/consumer-complaints/search/api/v1/`.
Parameters: `{"format": "csv", "date_received_min": "2026-08-03", "date_received_max": "2026-10-31", "product": "Credit card"}`.
Request started UTC: `2026-11-02T00:31:44.845Z`. Retrieved UTC: `2026-11-02T00:31:47.422Z`.
HTTP status: `200`. Source Date: `Mon, 02 Nov 2026 00:31:45 GMT`. Raw body SHA-256: `ba766e8dc9a04aeb162d58a22b3b0627d7cc9644179a39b39e5688f8bfb07ebd`.

```text
HTTP/1.1 200 OK
Content-Type: text/csv
Server: envoy
content-disposition: attachment; filename="complaints-2026-11-01_19_19.csv"
Access-Control-Allow-Origin: https://cfpb.github.io
Access-Control-Allow-Methods: GET
Allow: OPTIONS, GET
Content-Security-Policy: style-src 'self' 'unsafe-inline' *.consumerfinance.gov *.googletagmanager.com fonts.googleapis.com api.mapbox.com www.ssa.gov/accessibility/andi/; media-src 'self' *.consumerfinance.gov; frame-src 'self' *.consumerfinance.gov *.googletagmanager.com *.google-analytics.com www.youtube.com *.qualtrics.com mailto:; img-src 'self' *.cfpb.gov *.consumerfinance.gov www.ecfr.gov s3.amazonaws.com img.youtube.com *.google-analytics.com *.googletagmanager.com api.mapbox.com *.tiles.mapbox.com blob: data: www.gravatar.com *.qualtrics.com *.mouseflow.com i.ytimg.com www.ssa.gov/accessibility/andi/; default-src 'self'; connect-src 'self' *.consumerfinance.gov dap.digitalgov.gov *.google-analytics.com *.tiles.mapbox.com api.mapbox.com bam.nr-data.net gov-bam.nr-data.net s3.amazonaws.com public.govdelivery.com *.mouseflow.com *.qualtrics.com raw.githubusercontent.com; font-src 'self' fonts.gstatic.com; script-src 'self' 'unsafe-inline' 'unsafe-eval' *.consumerfinance.gov dap.digitalgov.gov *.googleanalytics.com *.google-analytics.com *.googletagmanager.com api.mapbox.com js-agent.newrelic.com bam.nr-data.net gov-bam.nr-data.net *.youtube.com *.ytimg.com *.mouseflow.com *.geo.census.gov about: www.federalregister.gov *.qualtrics.com www.ssa.gov/accessibility/andi/ ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js
x-frame-options: SAMEORIGIN
Permissions-Policy: interest-cohort=()
x-content-type-options: nosniff
referrer-policy: same-origin
cross-origin-opener-policy: same-origin
x-envoy-upstream-service-time: 78
Date: Mon, 02 Nov 2026 00:31:45 GMT
Transfer-Encoding:  chunked
Connection: keep-alive
Connection: Transfer-Encoding
Strict-Transport-Security: max-age=31536000

Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-08-18T03:40:12.000Z,Credit card,General-purpose credit card or charge card,Problem with a purchase shown on your statement,Credit card company isn't resolving a dispute about a purchase on your statement,Company believes it acted appropriately as authorized by contract or law,NAVY FEDERAL CREDIT UNION,MN,55119,None,Web,2026-08-18T03:52:11.000Z,Closed with explanation,Yes,25473790
2026-08-16T02:42:32.000Z,Credit card,General-purpose credit card or charge card,Trouble using your card,Account sold or transferred to another company,None,CAPITAL ONE FINANCIAL CORPORATION,IN,46235,None,Web,2026-08-16T02:57:57.000Z,Closed with non-monetary relief,Yes,25411177
2026-08-20T20:04:13.000Z,Credit card,General-purpose credit card or charge card,Getting a credit card,Card opened without my consent or knowledge,None,"EQUIFAX, INC.",PA,18103,None,Web,2026-08-20T20:07:55.000Z,Closed with explanation,Yes,25611554

```

### Pull 1, prior, attempt 1

Request: GET https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1/?format=csv&date_received_min=2026-05-05&date_received_max=2026-08-02&product=Credit%20card
Host: `www.consumerfinance.gov`. Endpoint: `/data-research/consumer-complaints/search/api/v1/`.
Parameters: `{"format": "csv", "date_received_min": "2026-05-05", "date_received_max": "2026-08-02", "product": "Credit card"}`.
Request started UTC: `2026-11-02T00:31:47.531Z`. Retrieved UTC: `2026-11-02T00:31:50.004Z`.
HTTP status: `200`. Source Date: `Mon, 02 Nov 2026 00:31:47 GMT`. Raw body SHA-256: `3681c27201274dacb66facea8aa4028561a3ff552d2bcb572a6de6aa84294a15`.

```text
HTTP/1.1 200 OK
Content-Type: text/csv
Server: envoy
content-disposition: attachment; filename="complaints-2026-11-01_19_21.csv"
Access-Control-Allow-Origin: https://cfpb.github.io
Access-Control-Allow-Methods: GET
Allow: OPTIONS, GET
Content-Security-Policy: style-src 'self' 'unsafe-inline' *.consumerfinance.gov *.googletagmanager.com fonts.googleapis.com api.mapbox.com www.ssa.gov/accessibility/andi/; connect-src 'self' *.consumerfinance.gov dap.digitalgov.gov *.google-analytics.com *.tiles.mapbox.com api.mapbox.com bam.nr-data.net gov-bam.nr-data.net s3.amazonaws.com public.govdelivery.com *.mouseflow.com *.qualtrics.com raw.githubusercontent.com; default-src 'self'; img-src 'self' *.cfpb.gov *.consumerfinance.gov www.ecfr.gov s3.amazonaws.com img.youtube.com *.google-analytics.com *.googletagmanager.com api.mapbox.com *.tiles.mapbox.com blob: data: www.gravatar.com *.qualtrics.com *.mouseflow.com i.ytimg.com www.ssa.gov/accessibility/andi/; script-src 'self' 'unsafe-inline' 'unsafe-eval' *.consumerfinance.gov dap.digitalgov.gov *.googleanalytics.com *.google-analytics.com *.googletagmanager.com api.mapbox.com js-agent.newrelic.com bam.nr-data.net gov-bam.nr-data.net *.youtube.com *.ytimg.com *.mouseflow.com *.geo.census.gov about: www.federalregister.gov *.qualtrics.com www.ssa.gov/accessibility/andi/ ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js; frame-src 'self' *.consumerfinance.gov *.googletagmanager.com *.google-analytics.com www.youtube.com *.qualtrics.com mailto:; media-src 'self' *.consumerfinance.gov; font-src 'self' fonts.gstatic.com
x-frame-options: SAMEORIGIN
Permissions-Policy: interest-cohort=()
x-content-type-options: nosniff
referrer-policy: same-origin
cross-origin-opener-policy: same-origin
x-envoy-upstream-service-time: 55
Date: Mon, 02 Nov 2026 00:31:47 GMT
Transfer-Encoding:  chunked
Connection: keep-alive
Connection: Transfer-Encoding
Strict-Transport-Security: max-age=31536000

Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-07-08T03:52:15.000Z,Credit card,Store credit card,Getting a credit card,Card opened without my consent or knowledge,Company has responded to the consumer and the CFPB and chooses not to provide a public response,SYNCHRONY FINANCIAL,GA,30122,Servicemember,Web,2026-07-08T04:42:27.000Z,Closed with explanation,Yes,23970492
2026-07-28T00:37:37.000Z,Credit card,Store credit card,Fees or interest,Charged too much interest,Company has responded to the consumer and the CFPB and chooses not to provide a public response,SYNCHRONY FINANCIAL,NJ,08107,None,Web,2026-07-28T13:48:15.000Z,Closed with monetary relief,No,24660085
2026-08-01T23:36:10.000Z,Credit card,General-purpose credit card or charge card,Problem with a purchase shown on your statement,Card was charged for something you did not purchase with the card,Company has responded to the consumer and the CFPB and chooses not to provide a public response,"BANK OF AMERICA, NATIONAL ASSOCIATION",CA,90012,None,Web,2026-08-01T23:47:57.000Z,Closed with monetary relief,Yes,24858656

```

### Pull 2, current, attempt 1

Request: GET https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1/?format=csv&date_received_min=2026-08-03&date_received_max=2026-10-31&product=Credit%20card
Host: `www.consumerfinance.gov`. Endpoint: `/data-research/consumer-complaints/search/api/v1/`.
Parameters: `{"format": "csv", "date_received_min": "2026-08-03", "date_received_max": "2026-10-31", "product": "Credit card"}`.
Request started UTC: `2026-11-03T05:28:17.048Z`. Retrieved UTC: `2026-11-03T05:28:34.316Z`.
HTTP status: `200`. Source Date: `Tue, 03 Nov 2026 05:28:31 GMT`. Raw body SHA-256: `679c3ac1f1b9b9107f1739a8079b798488c933e5e9581c18e9a27111c3e64c6f`.

```text
HTTP/1.1 200 OK
Content-Type: text/csv
Server: envoy
content-disposition: attachment; filename="complaints-2026-11-03_00_28.csv"
Access-Control-Allow-Origin: https://cfpb.github.io
Access-Control-Allow-Methods: GET
Allow: OPTIONS, GET
Content-Security-Policy: connect-src 'self' *.consumerfinance.gov dap.digitalgov.gov *.google-analytics.com *.tiles.mapbox.com api.mapbox.com bam.nr-data.net gov-bam.nr-data.net s3.amazonaws.com public.govdelivery.com *.mouseflow.com *.qualtrics.com raw.githubusercontent.com; font-src 'self' fonts.gstatic.com; media-src 'self' *.consumerfinance.gov; script-src 'self' 'unsafe-inline' 'unsafe-eval' *.consumerfinance.gov dap.digitalgov.gov *.googleanalytics.com *.google-analytics.com *.googletagmanager.com api.mapbox.com js-agent.newrelic.com bam.nr-data.net gov-bam.nr-data.net *.youtube.com *.ytimg.com *.mouseflow.com *.geo.census.gov about: www.federalregister.gov *.qualtrics.com www.ssa.gov/accessibility/andi/ ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js; frame-src 'self' *.consumerfinance.gov *.googletagmanager.com *.google-analytics.com www.youtube.com *.qualtrics.com mailto:; img-src 'self' *.cfpb.gov *.consumerfinance.gov www.ecfr.gov s3.amazonaws.com img.youtube.com *.google-analytics.com *.googletagmanager.com api.mapbox.com *.tiles.mapbox.com blob: data: www.gravatar.com *.qualtrics.com *.mouseflow.com i.ytimg.com www.ssa.gov/accessibility/andi/; style-src 'self' 'unsafe-inline' *.consumerfinance.gov *.googletagmanager.com fonts.googleapis.com api.mapbox.com www.ssa.gov/accessibility/andi/; default-src 'self'
x-frame-options: SAMEORIGIN
Permissions-Policy: interest-cohort=()
x-content-type-options: nosniff
referrer-policy: same-origin
cross-origin-opener-policy: same-origin
x-envoy-upstream-service-time: 279
Date: Tue, 03 Nov 2026 05:28:31 GMT
Transfer-Encoding:  chunked
Connection: keep-alive
Connection: Transfer-Encoding
Strict-Transport-Security: max-age=31536000

Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-08-18T03:40:12.000Z,Credit card,General-purpose credit card or charge card,Problem with a purchase shown on your statement,Credit card company isn't resolving a dispute about a purchase on your statement,Company believes it acted appropriately as authorized by contract or law,NAVY FEDERAL CREDIT UNION,MN,55119,None,Web,2026-08-18T03:52:11.000Z,Closed with explanation,Yes,25473790
2026-08-16T02:42:32.000Z,Credit card,General-purpose credit card or charge card,Trouble using your card,Account sold or transferred to another company,None,CAPITAL ONE FINANCIAL CORPORATION,IN,46235,None,Web,2026-08-16T02:57:57.000Z,Closed with non-monetary relief,Yes,25411177
2026-08-20T20:04:13.000Z,Credit card,General-purpose credit card or charge card,Getting a credit card,Card opened without my consent or knowledge,None,"EQUIFAX, INC.",PA,18103,None,Web,2026-08-20T20:07:55.000Z,Closed with explanation,Yes,25611554

```

### Pull 2, prior, attempt 1

Request: GET https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1/?format=csv&date_received_min=2026-05-05&date_received_max=2026-08-02&product=Credit%20card
Host: `www.consumerfinance.gov`. Endpoint: `/data-research/consumer-complaints/search/api/v1/`.
Parameters: `{"format": "csv", "date_received_min": "2026-05-05", "date_received_max": "2026-08-02", "product": "Credit card"}`.
Request started UTC: `2026-11-03T05:28:34.962Z`. Retrieved UTC: `2026-11-03T05:28:39.813Z`.
HTTP status: `200`. Source Date: `Tue, 03 Nov 2026 05:28:36 GMT`. Raw body SHA-256: `f709b424b756ad1115329ac5ab449f273f62bf0ca7bb55969f0a3efcedb38cf3`.

```text
HTTP/1.1 200 OK
Content-Type: text/csv
Server: envoy
content-disposition: attachment; filename="complaints-2026-11-03_00_28.csv"
Access-Control-Allow-Origin: https://cfpb.github.io
Access-Control-Allow-Methods: GET
Allow: OPTIONS, GET
Content-Security-Policy: img-src 'self' *.cfpb.gov *.consumerfinance.gov www.ecfr.gov s3.amazonaws.com img.youtube.com *.google-analytics.com *.googletagmanager.com api.mapbox.com *.tiles.mapbox.com blob: data: www.gravatar.com *.qualtrics.com *.mouseflow.com i.ytimg.com www.ssa.gov/accessibility/andi/; frame-src 'self' *.consumerfinance.gov *.googletagmanager.com *.google-analytics.com www.youtube.com *.qualtrics.com mailto:; style-src 'self' 'unsafe-inline' *.consumerfinance.gov *.googletagmanager.com fonts.googleapis.com api.mapbox.com www.ssa.gov/accessibility/andi/; media-src 'self' *.consumerfinance.gov; font-src 'self' fonts.gstatic.com; connect-src 'self' *.consumerfinance.gov dap.digitalgov.gov *.google-analytics.com *.tiles.mapbox.com api.mapbox.com bam.nr-data.net gov-bam.nr-data.net s3.amazonaws.com public.govdelivery.com *.mouseflow.com *.qualtrics.com raw.githubusercontent.com; default-src 'self'; script-src 'self' 'unsafe-inline' 'unsafe-eval' *.consumerfinance.gov dap.digitalgov.gov *.googleanalytics.com *.google-analytics.com *.googletagmanager.com api.mapbox.com js-agent.newrelic.com bam.nr-data.net gov-bam.nr-data.net *.youtube.com *.ytimg.com *.mouseflow.com *.geo.census.gov about: www.federalregister.gov *.qualtrics.com www.ssa.gov/accessibility/andi/ ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js
x-frame-options: SAMEORIGIN
Permissions-Policy: interest-cohort=()
x-content-type-options: nosniff
referrer-policy: same-origin
cross-origin-opener-policy: same-origin
x-envoy-upstream-service-time: 132
Date: Tue, 03 Nov 2026 05:28:36 GMT
Transfer-Encoding:  chunked
Connection: keep-alive
Connection: Transfer-Encoding
Strict-Transport-Security: max-age=31536000

Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-07-23T03:24:43.000Z,Credit card,General-purpose credit card or charge card,Problem with a purchase shown on your statement,Credit card company isn't resolving a dispute about a purchase on your statement,Company has responded to the consumer and the CFPB and chooses not to provide a public response,TRUIST FINANCIAL CORPORATION,MD,20906,None,Web,2026-07-23T03:53:20.000Z,Closed with explanation,Yes,24504508
2026-07-25T20:11:26.000Z,Credit card,Store credit card,Closing your account,Company closed your account,Company has responded to the consumer and the CFPB and chooses not to provide a public response,SYNCHRONY FINANCIAL,NY,124XX,Older American,Web,2026-09-21T17:27:54.000Z,Closed with explanation,Yes,24606658
2026-07-31T09:12:07.000Z,Credit card,General-purpose credit card or charge card,Problem with a purchase shown on your statement,Credit card company isn't resolving a dispute about a purchase on your statement,None,JPMORGAN CHASE & CO.,NY,11360,Older American,Referral,2026-07-31T18:51:17.000Z,Closed with explanation,Yes,24823561

```
