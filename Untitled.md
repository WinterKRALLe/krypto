blokový x proudový přístup - proudový přístup šifruje data po jednotlivých bitech nebo bytech průběžně, zatímco blokový přístup šifruje data po blocích o nějaké velikosti.
Iterativní postup je metoda, která opakuje jednoduché kroky, během kterých se klíč mění a šifruje datový blok.
inicializační vektor - náhodný prvek, pomocí něj a klíče se generuje provozní klíč šifry
CBC Cipher Block Chaining - jeden z možných režimů činnosti, metoda, která šifruje text po blocích a používá předchozí šifrovaný blok jako vstup pro šifrování následujícího bloku, aby se zabránilo možnosti analýzy frekvence.
frekvenční analýza - vyhodnocuje četnost daných znaků v daném jazyce ve zprávě, používá se v kryptoanalýze
statistická analýza textu je postavená na frekvenci znaků a na poměru samohlásek, souhlásek
4 způsoby šifrování pomocí chaosu - maskování, klíčování, CML, modulace - popisují, jakým způsobem se šifrují data o větším objemu dat, než je velikost bloku a jakým způsobem se operuje s inicializačním vektorem.
Princip chaotického maskování je využívat chaotické systémy k náhodnému přemístění nebo překrytí informací pro zlepšení bezpečnosti kryptografického systému.
Princip chaotického klíčování je využívat chaotické systémy k generování náhodných klíčů pro zlepšení bezpečnosti kryptografického systému.
Princip modulace je proces přenášení informace na signálu, který se používá pro přenos informace, kdy se vlastnosti signálu (fáze, amplituda, frekvence) mění podle informace, kterou se přenáší. (vysílačky)



RSA x DSA - (Číselné síťové pole GNFS) stojí na faktorizaci prvočísel x stojí na diskrétním logaritmu
ECC stojí na diskrétním logaritmu eliptických křivek, řeší se Pollardeho algoritmem pro diskrétní logaritmus, časová náročnost je exponenciální, má menší klíče než RSA

Vernamova šifra - proč je neprolomitelná - Spočívá v posunu každého znaku zprávy o náhodně zvolený počet míst v abecedě. Protože brute-force vede na všechny výsledky v daném jazyce a my nevíme který je správný.

metody pro prolomení vigenérovských šifer - kasiského metoda, index koincidence
3DES je šifrovací algoritmus, který využívá tři růůzné klíče pro šifrování dat, zatímco EDE2  používá dva klíče pro šifrování a jeden klíč pro dešifrování a provádí šifrování-dešifrování-šifrování.

Synchronizace chaotických systémů je proces, kdy se dva nebo více chaotických systémů dostávají do stejného stavu nebo do stavů, které se vzájemně ovlivňují.
- může být také využívána ke zlepšení stability systému nebo k dosažení určitých cílů, jako jsou například synchronizace různých komunikačních systémů.

Shamirův tříprůchodový protokol funguje takto:
1.  První strana (A) generuje náhodný tajný klíč a šifruje ho pomocí veřejného klíče druhé strany (B).
2.  Zaslaný zašifrovaný klíč se dešifruje pomocí soukromého klíče druhé strany (B).
3.  Druhá strana (B) poté šifruje klíč zpět pomocí veřejného klíče první strany (A) a posílá ho zpět.
4.  První strana (A) dešifruje klíč pomocí svého soukromého klíče a potvrzuje, že je to správný klíč.


Autokláv OT: Klíčové slovo slouží k “nastartování” substituce, dále se jako klíčové slovo používá samotný otevřený text.


Hybridní šifrování (princip) - 
- “Hlavní” data (velká velikost) jsou šifrovány rychlou symetrickou šifrou
- Klíč k symetrické šifře (symetrický či konvenční klíč) je pak zašifrován asymetrickou šifrou
- Obě části (zašifrovaná data a zašifrovaný symetrický klíč) jsou spojeny do jednoho balíku a odeslány
- Naprosto běžný standard HTTPS, FTPS, SSH, SSL protokolů
Symetrické šifry ( ​ k zašifrování se používá klíč, který je nutná sdílet s příjemcem, který ho díky tomuto klíči dešifruje)
Výhody:
- Jednoduchost šifrovacího a dešifrovacího algoritmu.
- Rychlé algebraické/binární operace často opakované v iteracích.
- Rychlost (stovky i více Mbit/s).
Nevýhody:
- Nutnost sdílení/přenosu klíče předem nebo při inicializaci komunikace jiným zabezpečeným kanálem (sms, osobní domluva, jiné algoritmy a workflow).
- Při komunikaci s více účastníky, nutnost velkého množství klíčů 
Blokové šifry​ - Data jsou rozdělena do bloků konstantní délky a následně zašifrována​ (AES, DES)
	- ​Režimy činnosti ​- způsoby řetězení dat z výstupu na vstup, aby se nešifrovali stejné bloky (CBC, ECB)
Proudové šifry​ - (bit po bitu) aplikace pro přenos telekomunikací/datastream. ​(RC4)
Polygrafická substituce - Playfair, Bifid/Trifid, Hillova šifra
Monoalfabetická šifra - Caesarova, ATBASH
Polyalfabetická šífra - Vigenorova, Vernamova
Transpoziční šifry - Zubatka
Hybridní šifry (transpozice/substituce) - ADFGVX, PGP
Symetrické proudové šifry - FISH, RC4
Symetrické blokové šifry - DES, AES, IDEA, CAST, BLOWFISH
Asymetrické šifry (s veřejným klíčem) – RSA, ElGamal
Asymetrické protokoly – Diffie Helman

S-box je tabulka, která přiřazuje každému vstupnímu byte hodnotu výstupního byte
DES využívá kombinaci dvou kryptografických technik substituce (tj.
nahrazení jisté bitové hodnoty jinou hodnotou na základě S-box) a permutace
(tj. jistá záměna pořadí jednotlivých bitů v bloku).

Dictionary attack, Brute force attack, Lineární kryptoanalýza, Diferenciální kryptoanalýza, side channel
![[Pasted image 20230118220306.png]]
![[Pasted image 20230119000238.png]]
Vstupní parametry rundové funkce jsou obvykle:
-   Klíč : Klíč se používá pro šifrování a dešifrování dat.
-   Data k šifrování : Data, která se mají šifrovat nebo dešifrovat
-   Číslo rundy : Ukazuje, na které rundě se právě nacházíme.
Rundová funkce vrací zašifrované nebo dešifrované data. Tyto data se použijí jako vstup pro další rundu, dokud se neprovede požadovaný počet rund.