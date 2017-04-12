## h2. a) Tee tämän kotitehtävän raportti GitHubiin MarkDownilla 

Käynnistin Linuxin( Xubuntu 16.04 LTS amd64) ja syötin komennon sudo apt-get update, saadakseni koneeni päivitettyä tehtävää varten. Tehtävää varten kirjauduin Githubiin ja loin tälle oman repositaryn nimeltä Linux sekä readme tiedoston ja lisenssitiedoston. Käytin tässä apuna Tero karvisen ohjeita: http://terokarvinen.com/2016/publish-your-project-with-github

## b) Tee puppet-moduli, joka tekee asetukset jollekin komentorivi- tai graafisen käyttöliittymän ohjelmalle.

Asensin koneeseen Puppetin ja moduulin tekoa varten siirryin /etc/puppet/modules kansioon ja loin sinne kansion lamp ja sen alle kansion manifests jonka sisälle loin init.pp tiedoston.
Käytin lähteenäni https://www.digitalocean.com/community/tutorials/getting-started-with-puppet-code-manifests-and-modules olevaa tutoriaalia jonka pohjalta tein oman moduulini.
sudo puppet apply -e 'class{lamp:}' komennolla saamme moduulin toimimaan 

```
**Lähteet**
http://terokarvinen.com/2017/aikataulu-%E2%80%93-palvelinten-hallinta-ict4tn022-2-%E2%80%93-5-op-uusi-ops-loppukevat-2017-p2
https://www.digitalocean.com/community/tutorials/getting-started-with-puppet-code-manifests-and-modules
```

