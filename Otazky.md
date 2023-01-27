<h3>Chaos</h3>
Chaos leží na pomezí mezi stochastismem a determinismem - projevuje se
stochasticky, ale je tam přítomna “dynamika na pozadí
o Tohoto jevu se pak využívá v Kryptologii - precizní nastavení systémů je klíčem k
zachování komunikace - tedy že systém ”neujede” někam mimo oblast řešení
<h3>Režimy činnosti</h3>
metody pro šifrování více než jednoho bloku dat, používají se k zajištění bezpečnosti při šifrování dat větších než jeden blok, kdy klasický kryptografický algoritmus by nebyl dostačující. Režimy činnosti jsou Electronic Code Book (ECB), Cipher Block Chaining (CBC), Cipher Feedback (CFB) a Output Feedback (OFB).
<h3>Co to je Substituce/Transpozice</h3>
substituce = nahrazování znaků
transpozice = změna pořadí znaků
<h3>co to je Diffie-Hellman</h3>
protokol pro sestavení symetrického klíče pro komunikaci na internetu.
o Protokol je postaven na jednocestné funkci diskrétní logaritmus
o Pro zamezení útoku na tento protokol (man in the middle) je nutné aplikovat
digitální podpisy a certifikáty pro autorizaci sdílených údajů.

-Nevýhoda monoalfabetických substitučních šifer

<h3>co to je jednocestná funkce +příklad </h3>
- Ze vstupu lze snadno spočítat výstup, z výstupu je však velmi obtížné nalézt
vstup. např.:
- Násobení a zpětná faktorizace prvočísel
- Problematika Diskrétního logaritmu (DLP)
- Problematika Diskrétního logaritmu eliptických křivek (ECDLP)
- Komplexní Modulární aritmetika
<h3>STEGANOGRAFIE</h3>
Obor kryptologie jehož úkolem je “schovávání” informací, tak aby nebyly viditelné. Při steganografii informaci nešifrujeme, ale “pouze” ji skrýváme. 
Fyzická Steganografie (Technická)
- Různé technické postupy pro skrytí informace
Digitální Steganografie
- Využití veškerých nástrojů a možností digitální komunikace
- Především ukrývání zpráv do multimediálních souborů
- LSB spočívá v neschopnosti lidského oka poznat rozdíl mezi dvěma barvami, které se liší právě v nejméně významném bitu
- nesmí to být kompresní
- Do TIFF obrázku 1024 x 768 bodů (24 bit) lze vměstnat až 288 kB dat
Tištěná Steganografie (Lingvistická) (stegotext)
- Modifikace nosného textu, tak aby ukryl tajný text
- nulové šifry (nezašifrované zprávy) - skutečná zpráva je obsažena v textu
jiné, neškodně vypadající.
Změna řezu písma, Změna velikosti významných znaků, Změna barvy, sytosti, Nepatrná změna polohy znaků, slov, řádků, Rozložení dokumentu - mezery navíc apod., Whitespaces v HTML kódu
Stegoanalýza je opakem steganografie. Zabývá se detekcí nebo odhadem
skryté informace.
<h3>Klíčový prostor</h3>
Počet všech možných klíčů v daném systému (kapacita abecedy, délka klíče)
<h3>Velikost bloků u blokových šifer (64-256 bitů)</h3>
<h3>Eliptické křivky</h3>
- Jedná se o analogii kryptosystému s veřejným klíčem, ve kterých je modulární
aritmetika nahrazena operacemi nad eliptickou křivkou (ECC), mají menší délku klíčů
y^2 = x^3 + a * x + b
D = −16(4a^3 + 27b^2) ≠ 0
y^2 => pro každé x rovnice má 2 řešení:
y = sqrt(x^3 + a * x +  b)
-y = -sqrt(x^3 + a * x +  b)
<h3>Brute force</h3>
Teoreticky vždy úspěšný postup (kromě Vernamovy šifry), ale prakticky
proveditelný jen pro malé množství klíčů.
Procházení všech možných kombinací klíčů nebo hesla, aby skončil, tak musí vědět co hledá
Existují modifikace - slovníkový útok hrubou silou - vyzkoušení všech možných
klíčů ze “slovníku” nejčastěji používaných klíčů a jejich kombinací.
<h3>Side-channel útok</h3>
Analyzuje ne-kryptografické informace, které se dostávají během kryptografické operace (např. spotřeba energie, teplota, čas, atd.) pro získání informací o klíči nebo jiných kryptografických parametrech.
<h3>SUBSTITUČNÍ ŠIFRY</h3>
MONOALFABETICKÁ, HOMOFONNÍ, POLYALFABETICKÁ, POLYGRAFICKÁ
<h3>Butterfly effect</h3>
Používá se k popisu teoretického principu chaosu. Tento princip říká, že i malá změna v počátečních podmínkách může mít v budoucnu velký dopad na výsledek. Používá se k popisu nepredikovatelnosti a nestability.
<h3>LAVINOVÝ EFEKT</h3>
Vlastnost hashovacích funkcí označující změnu výstupu v závislosti na změně vstupu

JAK LZE PROLOMIT SUBSTITUČNÍ ŠIFRU - brute force, frekvenční analýzou, obuškovou metodou
KVANTOVÁ KRYPTOGRAFIE JE SYMETRICKÁ, protože se používá stejný klíč pro šifrování a dešifrování dat a klíče jsou generovány z kvantových stavů
AES VELIKOSTI KLÍČŮ - 128, 192, 256
<h3>KRYPTOLOGIE</h3>
technický obor zastřešující celkově 3 podobory a zabývající se ochranou přenosu informace. Kryptologie = Kryptografie + Kryptoanalýza + Steganografie.
- KRYPTOGRAFIE - technický obor zabývající se tvorbou, vývojem, inovacemi,
standardizacemi šifrovacích algoritmů a jejich používáním.
o KRYPTOANALÝZA - technický obor zabývající se dešifrováním zachycené komunikace, dále testováním odolnosti nových algoritmů, možnostmi útoků, odhalováním “zadních vrátek”, penetračními testy atd...
VLASTNOSTI HASHOVACÍCH FUNKCÍ - bezkoliznost, jednosměrnost
DES NENÍ BEZPEČNÁ
TVRZENÍ O SYMETRICKÉ/ASYMETRICKÉ KRYPTOGRAFII - ASYMETRICKÁ JE POMALEJŠÍ, SYMETRICKÁ MÁ KOMPLIKOVANĚJŠÍ DISTRIBUCI KLÍČŮ
AKTIVITY KRYPTOANALÝZY - dešifrování zachycené komunikace, testování odolnosti nových algoritmů, analýza možných útoků na šifrovací algoritmus
ASYMETRICKÁ KRYPTOGRAFIE NEVYUŽÍVÁ JEDNOSMĚRNÉ FUNKCE.
<h3>ZÁKLADNÍ PRAVIDLA KRYPTOLOGIE</h3>
1. stejným klíčem by neměly být nikdy zašifrovány dva různé texty
2. pokud je to možné, kombinujeme se steganografickou technikou
3. klíč by měl být co nejméně uhodnutelný
4. dbát na dostatečnou délku klíče
