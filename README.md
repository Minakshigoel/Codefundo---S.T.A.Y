# Codefundo++

## Idea - S.T.A.Y Reliable
**The purpose of our idea is to minimize fraudulent cases and make the whole election process more reliable and secure.**

### Existing Problems:

1. A person can be forced/wants to give multiple votes in case if the whole felicitating group is also corrupted.
2. A person can have more than one voter cards, if:
    - He/she is living in a location other than hometown.
    - If applied more than once because the process got delayed.
    which can lead to multiple votes from a single person. Though it can be avoided by the usage of ink, it comes with a hack as described in the next point.
3. The ink used to mark on the finger is removable (by the usage of some chemical/oil/papaya extract), so a person can vote more than once.
4. Even after the person dies, the person’s name remains in the voter’s list, which can be misused.

### Proposed Solution:

We propose to have a system where all the Voter IDs will be linked to Aadhaar’s biometric details i.e. fingerprint and iris scan, which will follow a process as mentioned below:

- The EVM will be connected with a fingerprint and iris scanner, with additional small circuitry.
- The person will first give his/her biometric details (if fingerprint works than its enough, else scan the iris).
- The scanner will fetch the identity details from the Aadhaar database and will look for the entry into the server.
- If no entry found, i.e. a fresh entry, person's details will be stored into the server, followed by an indication of the green signal by the scanner and enable the EVM for the vote input for the reasonable amount of time to cast the vote.
- Else, if entry is found, i.e. trying to cast the vote for the second time, providing an indication of the red signal and an alarm alerting officials.

#### This solution will rectify the above problems in the following ways:

1. Ensure that a person votes only once.
2. Invalidate the other voter IDs belonging to the same person.
3. Even if the person removes the ink, repetitive fingerprint scan will deny the access.
4. Now if a person dies, and the name still appears in the voter's list, no other person can vote on his/her behalf.


