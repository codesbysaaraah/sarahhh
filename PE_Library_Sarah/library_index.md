# Library Index · Member Services Desk at a Public Library
Prefix: LB · Owner: Sarah · Date: 2026_10_15 · All data in this library is invented.

## Templates
| Template | Task | Variables | Version | Status |
|---|---|---|---|---|
| LB-Reply-Inquiry | Answer a member's question | [INPUT_TEXT] [FACTS] [LANGUAGE] [TONE] [MAX_WORDS] | v1 | Approved |
| LB-Sort-Requests | Sort member requests | [INPUT_TEXT] [LANGUAGE] [TONE] [MAX_WORDS] | v1 | Approved |
| LB-Soften-Note | Friendlier staff note | [INPUT_TEXT] [LANGUAGE] [TONE] [MAX_WORDS] | v1 | Approved |
| LB-Draft-Reminder | Due-date reminder | [DUE_DATE] [BOOK_TITLE] [FACTS] [LANGUAGE] [TONE] [MAX_WORDS] | v1 | Approved |
| LB-Mask-Details | Mask member details | [INPUT_TEXT] [MAX_WORDS] | v1 | Approved |

## Shared blocks
| File | Content | Used by |
|---|---|---|
| blocks/LB-Facts-v1_2026_10_15.md | The 7 Library Facts | LB-Reply-Inquiry, LB-Draft-Reminder |

## Rules file
| File | Content |
|---|---|
| rules/LB-Rules-v1_2026_10_15.md | The 5 fixed rules, written inside every template |

## The five [LANGUAGE] values
| Value | Meaning |
|---|---|
| Arabic | Answer in Arabic only |
| English | Answer in English only |
| Automated (default) | Reply in the main language of the input |
| Bilingual | Two separate versions: Arabic, then English |
| Mixed | One reply that merges Arabic and English |

## Change log
| Date | File | Change |
|---|---|---|
| 2026_10_15 | All | Library created, five templates approved at 5/6/5 (see Test_Results_Report.pdf) |
