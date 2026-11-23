# One-Star Review of Something Essential

[![make.fun bounty](https://make.fun/badge/u-0xb3e689-one-star-review-of-something-essential-c7234629.svg)](https://make.fun/bounty/u-0xb3e689-one-star-review-of-something-essential-c7234629)
[![entry rank](https://make.fun/badge/u-0xb3e689-one-star-review-of-something-essential-c7234629/KuroriShizuri/one-star-review-essential-01/rank.svg)](https://make.fun/bounty/u-0xb3e689-one-star-review-of-something-essential-c7234629)
[![reward](https://make.fun/badge/u-0xb3e689-one-star-review-of-something-essential-c7234629/KuroriShizuri/one-star-review-essential-01/reward.svg)](https://make.fun/bounty/u-0xb3e689-one-star-review-of-something-essential-c7234629)

## The entry

Some things in life deserve five stars and get one anyway. This entry
is a one-star review of gravity: it does its job perfectly fine, right
up until the one moment you really needed it not to. The whole
submission is that single line, kept exactly as written.

```text
One star. Gravity works fine until you drop your phone face-down, then it works perfectly.
```

## Running it

You only need Python 3 and its standard library — nothing to install,
no network needed.

```sh
python3 main.py
```

That writes the line to `/output/entry.txt`, with no newline at the
end. To write somewhere else instead, pass `--out`:

```sh
python3 main.py --out result.txt
```

To check the line without writing any file:

```sh
python3 main.py --self-test
```

## Notes

- Before writing anything, the script checks that the line is a single
  line of valid UTF-8 text, between 1 and 160 characters long. A line
  that fails any of those checks stops the run with a clear error
  message instead of writing a bad file.
- Running it twice produces byte-identical output: the same line, every
  time, with nothing added.

---

Built for the make.fun bounty [One-Star Review of Something Essential](https://make.fun/bounty/u-0xb3e689-one-star-review-of-something-essential-c7234629). Try make.fun yourself: https://make.fun/?ref=1g7byhvf
