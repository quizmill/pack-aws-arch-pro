# AWS Certified Solutions Architect – Professional — quizmill pack

Unofficial hard-mode Quizmill learning pack for AWS Certified Solutions Architect – Professional (SAP-C02).

## Contents

- 40 original scenario-heavy multiple-choice questions, each linked (`sourceRef` and "Read more") to the AWS documentation page it rests on
- 7 categories: Organizations/governance, hybrid networking, migration, DR, security, data, and cost
- Difficulty skewed toward professional-level architecture trade-offs

## Use

```sh
npx quizmill validate .
npx quizmill run .
```

Or from the Quizmill engine repo:

```sh
npm run pack:validate /path/to/pack-aws-arch-pro
npm run pack:use /path/to/pack-aws-arch-pro
npm run build
```

## Notes

This is an unofficial generated practice pack. It is not affiliated with, endorsed by, or sponsored by Amazon Web Services. AWS certification names are trademarks of Amazon Web Services, Inc.

Questions are marked `reviewStatus: draft` until human-reviewed.

Every question is original, written from the public AWS documentation and the SAP-C02 exam guide. No question is taken from community banks, official practice questions or exam dumps.

## Verification

On 2026-10-23 the whole bank went through the quizmill item evals: the deterministic lint (`--strict`), then a three-pass Claude review (solve without the key, guess the key from the options alone, and a rubric review for item-writing flaws) with `claude-fable-5-1`. The first run rated 38 of 40 items major, mostly for throwaway distractors and keys longer than every distractor. After the rewrite: lint reports 0 findings, the solve pass agrees with every key, and the review finds 0 fatal, 0 major and 3 minor items. Answer keys are spread across option positions.
