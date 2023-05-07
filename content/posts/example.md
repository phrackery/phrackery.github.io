---
title: "Example"
date: 2023-05-06T20:52:35-04:00
draft: false
---

hello darkness my old buddy. I've come to speak with you again.

you created this file in the blog top level folder using the commnad 
``` bash
hugo new posts/example.md
```
then you edited it with helix.

then when you finished editing it you manually changed the draft from `true` to `false`

now you will run `hugo` and `hugo server` to build the static webiste and start a local server to view changes, all within the top level folder of your blog

now to add it to git so its published to your site use these commands
```bash
git add .
git commit -m "First Commit, Nice!"
git push
```