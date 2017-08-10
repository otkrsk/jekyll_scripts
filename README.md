# Jekyll Scripts
These 2 scripts are used to generate the timestamp. One is used to insert it into the post, and the other is to append it to the filename.

## Usage
Just clone/copy the scripts into the root of your Jekyll directory. It's best to run the script inside the folder of which the file you want to manipulate is in. For example, if you want to rename posts in your draft folder, you do as follows:

### Script #1
```
# inside the `_posts` folder
../jekyll_insert_date name-of-your-post.md
```

This script is used with the command `./jekyll_insert_date _posts/2017-08-09_name-of-your-post.md`. This will insert the date on the `date` line in your post. The date generated is complete with the timezone. You can run this command as many times as you like whenever you want to update your post's date.

### Script #2
```
# inside the `_drafts` folder
../jekyll_generate_filename name-of-your-post.md
```

The result would be that the file would now have the current date appended to it, i.e., `2017-08-09_name-of-your-post.md`. This command can be used again even though the file already has a date appended to it. It will just rename that file with the new timestamp.
## Contributions

Feel free to add to or modify the scripts if you feel that it could be improved further. Thanks!
