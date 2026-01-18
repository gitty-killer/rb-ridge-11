# rb-ridge-11

A small Ruby tool that computes text statistics for ridge.

## Objective
- Provide quick text metrics for ridge documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate ridge drafts for repeated terms before review.
- Summarize ridge notes when preparing reports.

## Usage
ruby main.rb data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
