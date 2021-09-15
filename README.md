Alexis Murari

git checkout -b rebase

git add helloworld.py
git commit -m "c1"

git add helloworld.py
git commit -m "c2"

git checkout develop

git add helloworld.py
git commit -m "c3"

git add helloworld.py
git commit -m "c4"

git checkout rebase

git rebase develop