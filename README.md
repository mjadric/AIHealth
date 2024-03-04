# AIHealth

Upute za rad s gitom preko Colab-a:

1. Inicijalizacija repozitorija i kloniranje (radi se samo jednom na početku!):

!git init
!git clone <URL_of_your_repository>

-----------------------------------------

2. Rad s osobnom granom:

!git checkout -b naziv_grane

Povlačenje promjena s glavne grane (ako je potrebno)

!git pull origin main


3. Dodavanje, commitanje i pushanje promjena:

!git add .

!git commit -m "Commit message from notebook on development branch"

!git config --global user.email "your_email@example.com"

!git config --global user.name "Your Name"

!git push origin naziv_grane


