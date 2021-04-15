# h3 Versionhallinta

## Git ja GitHub

Tehtävään kuului tehdä sen raportti MarkDownina GitHub-varastoon. Git on versionhallintajärjestelmä, joka tekee tiedostoihin tehtyjen muutosten seuraamisesta helpompaa. 
Esimerkiksi kun editoidaan tiedostoa, git voi auttaa määrittelemään mikä muuttui, kuka 
muutti sen ja miksi. Se on hyödyllinen työn koordinoinnissa useamman henkilön projekteis
sa tai edistymisen seuraamisessa tallennuspisteiden avulla. Git ei ole ainoa saatavilla ole
va versionhallintajärjestelmä, mutta se on ylivoimaisesti suosituin. 

GitHub ei ole git vaan se on verkkosivu projektien hostaamista varten, jotka käyttävät git:iä. GitHub käyttää projektien organisointiin varastoja, yleensä yhtä varastoa käytetään yhden projek-
tin organisointiin. Varastoihin voi kuulua tiedostoja, kuvia, videoita, laskutaulukkoja 
tai mitä vaan projekti tarvitseekaan.

## git log, git diff ja git blame 

Git log on yksinkertainen ja tehokas työkalu, minkä avulla nähdään aiemmat aiemmat versiot varaston historiassa. Ajoin itse komennon varastossa, minkä olin luonut tätä tehtävää
varten.

	$ git log
	commit 11a65d103e2ec43c6494f82ab7376de504e2cb30 (HEAD -> main, origin/main, origin/HEAD)
	Author: Iiro Juntunen <bga263@myy.haaga-helia.fi>
	Date:   Thu Apr 15 15:44:21 2021 +0300

    Add h3versionhallinta

	commit d5e0a0415e22f263e9d2069c88e63fde42496664
	Author: Iiro Juntunen <bga263@myy.haaga-helia.fi>
	Date:   Thu Apr 15 15:40:54 2021 +0300

    Add h3versionhallinta

	commit 9639f21611e64c970e2649d644981effcf3a7472
	Author: Iiro Juntunen <bga263@myy.haaga-helia.fi>
	Date:   Thu Apr 15 14:39:03 2021 +0300

    UPDATE h3versionhallinta

commit bbf585719f722581f86997a2b71f5beaee9e1e84
Author: Iiro Juntunen <bga263@myy.haaga-helia.fi>
Date:   Thu Apr 15 14:37:16 2021 +0300

    ADD h3versionhallinta

commit 3876c1c63b616dd1a277f9a13d343415f7130399
Author: Iiro Juntunen <bga263@myy.haaga-helia.fi>
Date:   Thu Apr 15 14:30:43 2021 +0300

    Add README

Oletuksena git log listaa kaikki tehdyt muutokset käänteisessä aikajärjestyksessä eli tuorein ensin.
Tulosteesta näkyi varaston jokainen "commit", sen tarkistussumma, tekijän nimi ja sähköposti, 
päivämäärä ja viesti.
