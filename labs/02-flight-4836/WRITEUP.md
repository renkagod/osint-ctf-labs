# Writeup — Flight 4836 (spoilers)

## Phase 1

**Sources:** Aviation accident databases (e.g. airdisaster.ru).

**Aircraft:** Identify the accident entry for the 2024 Baku–Grozny crash.

**Reference:** https://airdisaster.ru/database.php?id=4836

**Flag:** `FLAG{19000630}` (factory serial)

## Phase 2

**Sources:** CVR transcript pages for the same incident.

**Task:** Locate where the crew accepts loss of satellite navigation and requests a specific arrival procedure (three English tokens, middle token digit-prefixed).

**References:**

- https://airdisaster.ru/cvr.php?id=34
- https://baza.io/posts/fb439a5b-f8ce-4398-88f4-7890dd82c404

**Flag:** `FLAG{REMKA@1X-ray@ARRIVAL}`

## Phase 3

**Task:** Non-GNSS approach — find the navaid frequency/identifier value they dial in (408) and encode as Roman numerals.

**Flag:** `FLAG{CDVIII}` (408 → CDVIII)
