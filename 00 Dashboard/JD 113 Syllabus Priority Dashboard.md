---
type: dashboard
subject: Basic Legal and Judicial Ethics
course_code: JD 113
school: Our Lady of Lourdes College Foundation
professor: Atty. Edmunds A. Yuzon Jr.
status: active
bar_weight: high
priority: P1
tags:
  - ethics/dashboard
  - jd-113
  - syllabus-map
  - priority
up: "[[Legal and Judicial Ethics MOC]]"
related:
  - "[[Practice of Law]]"
  - "[[Ethics Case Index]]"
  - "[[Practice of Law - Doctrine-Driven Syllabus Map]]"
  - "[[Rule 138 - Priority Anchor Map]]"
  - "[[CPRA Canon I - Syllabus Map]]"
---

# JD 113 Syllabus Priority Dashboard

Use this note for the **next week**. It does not replace the existing vault structure. It adds a syllabus-priority layer on top of the current doctrine-first system.

## Priority rule

| Priority | Meaning | Immediate action |
|---|---|---|
| P1 | Landmark / foundation / likely recit anchor | Read first, digest-check first, memorize doctrine first |
| P2 | Important supporting case or subtopic | Read after P1; link to doctrine map |
| P3 | Background / completeness | Add placeholder now; build later |
| P4 | Cleanup only | Rename, tag, or backlink only when convenient |

## P1 first-week queue

1. [[Practice of Law]]
2. [[Cayetano v. Monsod]]
3. [[Ulep v. The Legal Clinic, Inc.]]
4. [[The Practice of Law as "A Mere Privilege, Not a Right" in Philippine Legal Ethics|Practice of Law: A Mere Privilege, Not a Right]]
5. [[The Practice of Law as a Profession, Not a Business or Trade]]
6. [[Burbe v. Atty. Magulta]]
7. [[Admission to the Bar]]
8. [[Rule 138 - Priority Anchor Map]]
9. [[Pimentel v. Legal Education Board]]
10. [[Revised Lawyer's Oath]]
11. [[Signing of the Roll of Attorneys]]
12. [[Unauthorized Practice of Law]]
13. [[CPRA Canon I - Syllabus Map]]
14. [[Canon I - Independence]]
15. [[Merit-Based Practice]]

## P1 doctrine spine

| Syllabus area | Doctrine anchor | Main case anchors | Priority |
|---|---|---|---|
| Definition and nature of practice of law | [[Practice of Law]] | [[Cayetano v. Monsod]], [[Ulep v. The Legal Clinic, Inc.]], [[People vs. Simplicio Villanueva]] | P1 |
| Practice as privilege | [[The Practice of Law as "A Mere Privilege, Not a Right" in Philippine Legal Ethics|Practice of Law: A Mere Privilege, Not a Right]] | [[In Re Petition to Sign in the Roll of Attorneys, Michael Medado]], [[Aguirre v. Rana]] | P1 |
| Profession, not business | [[The Practice of Law as a Profession, Not a Business or Trade]] | [[Burbe v. Atty. Magulta]], [[Ulep v. The Legal Clinic, Inc.]], [[Rosario, Jr. v. De Guzman]] | P1 |
| Supreme Court control over the Bar | [[Admission to the Bar]] | [[Pimentel v. Legal Education Board]] | P1 |
| Rule 138 requirements | [[Rule 138 - Priority Anchor Map]] | [[In Re Application for Admission to the Philippine Bar of Vicente D. Ching]], [[In Re Petition to Re-acquire the Privilege to Practice Law, B.M. No. 2112]], [[Garrido v. Attys. Garrido and Valencia]] | P1 |
| Oath and Roll | [[Revised Lawyer's Oath]], [[Signing of the Roll of Attorneys]] | [[Katipunan v. Atty. Carrera]], [[Santos v. Atty. Paña]], [[Pante v. Atty. Tebelin]], [[In Re Petition to Sign in the Roll of Attorneys, Michael Medado]] | P1 |
| Unauthorized practice | [[Unauthorized Practice of Law]] | [[Ulep v. The Legal Clinic, Inc.]], [[Cambaliza v. Cristal-Tenorio]], [[Tan, Jr. v. Atty. Gumba]], [[Bonifacio v. Atty. Era and Atty. Bragas]] | P1 |
| CPRA Canon I | [[CPRA Canon I - Syllabus Map]] | [[Jacolbia v. Atty. Panganiban]], [[Judge Dumlao, Jr. v. Atty. Camacho]], [[Jimenez and Vizconde v. Atty. Verano, Jr.]], [[Vantage Lighting Philippines v. Atty. Diño, Jr.]], [[Olvida v. Gonzales]] | P1 |

## P2 queue

| Area | Case / note | Why P2 |
|---|---|---|
| Legal education | RA 7662 / LEB materials | Needed to understand [[Pimentel v. Legal Education Board]], but doctrine case comes first |
| Law student practice | [[Law Student Practice Rule]], [[Cruz v. Mina]] | Important but narrower than Rule 138 and unauthorized practice |
| Government lawyers and public officials | [[Public Officials and Private Practice]], [[Ziga v. Judge Arejola]], [[Office of the Court Administrator vs. Atty. Misael M. Ladaga]] | Likely distinction questions |
| Non-lawyer appearances | [[Appearance of Non-Lawyers]] | Highly testable, but after basic practice definition |
| Continuing requirements | [[Continuing Requirements for the Practice of Law]], [[Turla v. Atty. Caringal]] | Must know, but after admission and practice definition |

## P3 placeholders to build later

- [[Privileges of a Lawyer]]
- [[Foreign Lawyers]]
- [[Professional Tax]]
- [[Membership Dues]]
- [[Legal Aid]]
- [[Paralegals]]
- [[Cadastral Proceedings]]
- [[Labor Cases - Non-Lawyer Appearance]]
- [[Agrarian Reform Proceedings - Non-Lawyer Appearance]]
- [[Barangay Conciliation - Non-Lawyer Appearance]]
- [[Cases Under Expedited Procedure - Non-Lawyer Appearance]]
- [[Arbitration - Non-Lawyer Appearance]]

## Dataview starter blocks

```dataview
TABLE priority, status, bar_weight, doctrine
FROM "01 Core Doctrines" OR "02 CPRA" OR "05 Cases"
WHERE contains(tags, "jd-113") OR contains(tags, "practice-of-law") OR contains(tags, "canon-i")
SORT priority ASC, file.name ASC
```

```dataview
TABLE doctrine, priority, status
FROM "05 Cases"
WHERE priority = "P1"
SORT file.name ASC
```

## Rule for working with case digests

Do **not** rewrite existing digests. For each case, add only:

- doctrine backlink;
- priority metadata;
- related CPRA / Rule 138 anchor;
- recall question link;
- comparison-table link.

## First-week study loop

1. Read the doctrine note.
2. Read only the linked P1 cases.
3. Ask: what exact provision or rule does this case prove?
4. Add one bar trap.
5. Add three flashcards.
6. Link the case to the doctrine map.
