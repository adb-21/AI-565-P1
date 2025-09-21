# README.md

## Member 1
- BNumber: [Your BNumber]
- Name: [Your Name]

## Member 2
- BNumber: [Your BNumber]
- Name: [Your Name]

## Submission

Submit a text file (submission.txt) that contains the URL of the commit you want to submit. The file should contain only one line with the URL. The URL should be generated using the following command:

```bash
$ touch submission.txt
$ echo "https://github.com/bu-cs-465-565/$(basename -s .git $(git config --get remote.origin.url))/tree/$(git log --grep="$keyword" -n 1 --format="%H")" > submission.txt
```
