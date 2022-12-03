# advent of code

this repo contains my solutions for advent of code

## scores
### part 1

|day|time|rank|score|
|---|---|---|---|
|1|00:09:20|5035|0|
|2|00:13:22|4899|0|
|3|00:04:22|368|0|

### part 2

|day|time|rank|score|
|---|---|---|---|
|1|00:10:24|3863|0|
|2|00:14:26|2281|0|
|3|00:08:06|442|0|

## notes

to use the helper scripts in this repo, create a file named `.session`
containing your adventofcode.com session id

`get-input` creates a `./{year}/{day}` directory, copies `template.py` as
`solution.py`, and fetches your unique input from adventofcode.com and
saves it as `input.txt`

`update-score` downloads your personal statistics from adventofcode.com, and
converts their ascii table into markdown tables and replaces the contents of
the `scores` section in this readme file