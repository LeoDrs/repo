## Palvelinten hallinta H5

## Tehtävänanto

h5. Tee moduli git-varastoon ja kirjoita raportti sinne MarkDownilla.

## Aloitus

Aluksi ajan komennot

setxkbmap fi
sudo apt-get update

jonka jälkeen asennan gitin

sudo apt-get install git

Tämän jälkeen lisään tiedot itsestäni

git config --global user.email "firstname.lastname@example.com"
git config --global user.name "Firstname Lastname"

Seuraavaksi kloonaan repositorion jonka loin GitHub sivustolle.
Kopioin GitHubista repositorioni urlin ja syötän komennon

git clone https://github.com/LeoDrs/repo.git 
cd repo

Sen jälkeen luon tämän tiedoston komennolla

nano README.md

ja lähden kirjoittamaan raporttia. Ihan aluksi kokeilen miten markdown toimii
syöttämällä satunnaista esimerkkitekstiä. Kun esimerkkiteksti on valmis
syötän komennot

git add .
git commit
git pull
git push

ja README.md näkyy GitHubissa.

## Moduuli

Lisään repooni moduulin jonka tein tehtävässä H4.
Aluksi luon kansion "modules". Tähän kansioon kopioin tekemäni moduulin.

cd modules
mkdir mymodule
cd mymodule
mkdir manifests
cd manifests
nano init.pp

Kopioin tiedostoon "init.pp" kirjoittamani moduulin ja tallennan tiedoston.
Tässä vaiheessa tallennan tämän tiedoston 



