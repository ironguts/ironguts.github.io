A website for Iron Guts HEMA and SANDA club in Indonesia.

To deploy:
cd maindir
lein run
rsync -a --include='*/' --include='*.txt' --exclude='*' public/blog/ docs/
    then git push to main.
