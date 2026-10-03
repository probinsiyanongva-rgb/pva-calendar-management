# Calendar Management 101 — PVA Academy

A standalone, local-first foundation minicourse for aspiring virtual assistants.

## Curriculum
1. Why Calendar Skills Matter
2. Navigating Google Calendar & Creating Events
3. Time Zones & Scheduling Across Countries
4. Managing Multiple Calendars
5. Professional Scheduling & Meeting Coordination

## Completion
Learners must complete all lessons, every practice check, five verified lesson Proof Vault artifacts, the capstone checks, a verified sixth Proof Vault artifact for the capstone, a final reflection, and a learner name before the certificate unlocks.

## Local-first design
- Progress is stored in localStorage.
- Proof artifacts are stored in IndexedDB.
- Proof existence is verified against IndexedDB before lesson completion and certificate eligibility.
- Proof writes are serialized per lesson to avoid rapid-upload races.
- Imported JSON never creates proof artifacts and cannot unlock completion without local proof files.
- Proof files are not included in JSON backups; the five lesson proofs and the capstone screenshot must be re-uploaded on another browser/device.
- Certificate SVG uses XML-safe text escaping and a longer object-URL lifetime.
- Print CSS removes viewport/overflow constraints from the certificate path.

## Scope
This is not a Google Calendar masterclass. It teaches the practical calendar-management skills a beginner VA is likely to need for ordinary client work, with hands-on practice and proof.
