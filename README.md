# Infinity Commit

## Releases

### 1.0.1

```
Usage: infinity-commit [-h] -s <start> -e <end> -t <step> -p <path>
       [-A <author_name>] [-E <author_email>] [-C <committer_name>] [-M <committer_email>]

Options:
    -h, --help            Show this help message and exit
    -s, --start <start>   Start Datetime (dd/mm/yyyy hh:mm:ss)
    -e, --end <end>       End Datetime (dd/mm/yyyy hh:mm:ss)
    -t, --step <step>     Step Integer (minutes)
    -p, --path <path>     Repository Path (/path/to/repository)
    -A, --author-name     Author Name
    -E, --author-email    Author Email
    -C, --committer-name  Committer Name
    -M, --committer-email Committer Email

Example: infinity-commit -s '01/01/2020 00:00:00' -e '31/12/2020 23:59:59' -t 60 -p '/path/to/repository'
         -A 'Author Name' -E 'author@example.com' -C 'Committer Name' -M 'committer@example.com'
```
