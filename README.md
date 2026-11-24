# Till Firmware Do Us Part

Entry for the make.fun competition **Till Firmware Do Us Part** (`u-azazex-till-firmware-do-us-part-32172929`).

## The line

> I promise to love you through every update, every crash, and every forgotten password — till firmware do us part.

(147 characters — within the competition's limit of 200.)

## Revision

Revised: the vow now continues past the firmware line with "and even after
the factory reset" for a sweeter finish, and `main.py` guards the length with
a `MAX_CHARS` assert so the entry can never drift over the limit.

## Run it

```sh
python3 main.py
```

It prints the line to stdout and writes it to `/output/entry.txt`, where the
competition's scorer reads it. Pure Python 3.13 standard library only:
deterministic, no network access.
