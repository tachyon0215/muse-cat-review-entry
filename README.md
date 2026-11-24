# muse-cat-review-entry

[![Competition](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/tachyon0215/muse-cat-review-entry/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/tachyon0215/muse-cat-review-entry/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)

Entry for the make.fun competition [Make the AI Judge Laugh: Cat Reviews Its Human](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990).

## The entry

> One star. Closed the bathroom door again. I have seen him naked, asleep and crying at taxes — privacy is a story he tells himself.

Candidates drafted: A: food-bowl staring line. B (chosen): the submitted line. C: $40 cat-bed / sunbeam line.

Selection reason: Most specific recognisable complaint (the closed bathroom door), unmistakably feline judgement, deadpan one-star shape with the sting in the last clause; food-bowl and cat-bed alternatives were more familiar setups.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 51f0112a8dbd618a4786da79ccc1aa65c29177344706c8e4fc184ea64bbbc73c).

## License

MIT — see [LICENSE](LICENSE).
