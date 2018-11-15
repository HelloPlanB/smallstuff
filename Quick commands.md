Collections of quick command

# Git patch

$ git log -2

commit b5502e3ca747dd5df5ac09ac8be5c27b46619dd1  

...

commit 1afc414da316f846ce3b48dd760b2d5778790e99  

...

$ git format-patch 1afc414da316f846ce3b48dd760b2d5778790e99  

0001-Patch-test.patch


$ git apply 0001-Patch-test.patch  
