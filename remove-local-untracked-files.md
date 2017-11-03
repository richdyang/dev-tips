If you want to see which files will be deleted you can use the -n option before you run the actual command:
```bash
git clean -n
```

Then when you are comfortable (because it will delete the files for real!) use the -f option:
```
git clean -f
```

Here are some more options for you to delete directories, files, ignored and non-ignored files
To remove directories, run `git clean -f -d or git clean -fd`
To remove ignored files, run `git clean -f -X or git clean -fX`
To remove ignored and non-ignored files, run `git clean -f -x or git clean -fx`