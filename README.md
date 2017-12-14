
# Fleet

## Agency

- Maintains a list of valid identities
- Receives DataRequests, creates Operations
- Operations have Missions
  - Mission contains:
    - public/private key (never stored in the same place)
    - Request data (eg: a URL)
    - Worker class
    - DeadDrop location
- Missions have Assignments
  - Assignment
- Assignments may have one Result
- Result points to DeadDrop

## Extractor

* Receives message
* Extracts data
* Places data in dead drop
