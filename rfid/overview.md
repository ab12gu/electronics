## Summary

RFID (Radio-frequency identification)

- Electromagnetic fields to automatically identify and track tags attached to objects

| Type             | Frequency (US) | Frequency (EU) | Units |
|------------------|----------------|----------------|-------|
| Low (LF)         | 125-134        | same           | hz    |
| High (HF)        | 13.56          | same           | Mhz (10^6 Hz) |
| Ultra High (UHF) | 902-928        | 865-868        | Mhz (10^6 Hz) |

## Storage

LF (EM4100)

- UID (4 bytes)
    - written by manufacturer (unchangeable)

HF (Mifare classic)

- UID (4 bytes)
    - written by manufacturer (unchangeable)
- 16 bytes (1 block) * 4 blocks * 16 sectors = 1024 bytes (writable)

Some readers can read only a single HF or LF standard.

For cloning a card you need:

- T5577
- Changable UID

### Docs

- [RFID wiki page](https://en.wikipedia.org/wiki/Radio-frequency_identification)

### Vids

- [RFID How-To: Not only for Arduino](https://www.youtube.com/watch?v=vEkfa3OMvec&t=230s)
- [RFID Hacking and Cloning with Magic Cards, Proxmark3 and Arduino (T5577)](https://www.youtube.com/watch?v=eVIq3--O8bM)