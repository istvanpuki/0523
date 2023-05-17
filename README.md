# 0523
Egy teszt.

Valahogy így használd

Git telepítése a gépre
GitHub fiók létrehozása
Githubon csinálsz egy repositoryt.
Azt klónozod git clone (repo url-je)
cd-vel belépsz a mappába, ahová klónoztál a repót
git status lecsekkolod, hogy sikerült-e
git add (fájl neve)
git commit -m "Ide a commit üzenet"
git push (ezzel felmegy az online repoba githubra)


Új branchet tipikusan úgy szoktunk létrehozni, hogy checkoutoljuk is, ezért a leggyakrabban a checkout parancsot használjuk erre a -b mint branch opcióval:

git checkout -b UjBranchnev

Ha pedig csak át akarunk váltani egy másik branchre, azt is a checkouttal tehetjük meg:

git checkout master
