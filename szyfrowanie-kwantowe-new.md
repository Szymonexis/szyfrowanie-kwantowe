---
marp: true
theme: default
size: 16:9
math: mathjax
---

# Szyfrowanie Kwantowe

---

# Co to są kwanty? Co to są kubity?

**Bit** - to najmniejsza jednostka informacji w informatyce _klasycznej_. Przyjmuje wartości $0$ albo $1$.

**Kubit** - to najmniejsza jednostka informacji w informatyce _kwantowej_. Przyjmuje wartości pomiędzy superpozycją $(1,
0)$ a $(0, 1)$, a po pomiarze stanu kwantowego przyjmuje jedną z wartości $1$ lub $0$. Kubity można również łączyć
poprzez splatanie kwantowe.

---

# Kluczowe pojęcia

1. **Superpozycja:**
2. **Zasada nieoznaczoności Heisenberga**
3. **Splątanie kwantowe**

---

# Superpozycja

W mechanice kwantowej cząstki mogą istnieć w wielu stanach jednocześnie. To zjawisko, znane jako superpozycja, umożliwia kodowanie znacznie większej ilości informacji na pojedynczym kubicie (podstawowej jednostce informacji kwantowej) w porównaniu z bitami w klasycznym komputerze.

---

# Superpozycja

Kolokwialnie rzecz ujmując superpozycję, można przedstawić przy pomocy poniższego problemu:

> To jak kiedy próbujesz się zdecydować, czy chcesz jeść lody truskawkowe czy czekoladowe, i ktoś mówi, że możesz mieć
> trochę obu na raz. Dzięki temu komputery kwantowe mogą rozwiązywać trudne problemy szybciej niż zwykłe komputery, bo
> patrzą na wiele możliwości naraz, a nie tylko na jedną.

[//]: # (Tutaj żart o superpozycji xd)

[//]: # (
    Są trzy rodzaje ludzi na świecie
    Ci co rozumieją mechanikę kwantową
    Ci co nie rozumieją mechaniki kwantowej
    Oraz ci co jednoczenie rozumieją i nie rozumieją mechaniki kwantowej
)

---

# Zasada nieoznaczoności Heisenberga

Zasada nieoznaczoności Heisenberga to pomysł w fizyce kwantowej, który mówi nam, że istnieje pewne naturalne ograniczenie dotyczące tego, jak dokładnie możemy jednocześnie zmierzyć pewne właściwości cząstki. Konkretnie chodzi o pozycję i pęd cząstki.

Jeśli bardzo precyzyjnie zmierzymy pozycję cząstki, to nasza pewność co do jej pędu stanie się mniej precyzyjna, i odwrotnie. Innymi słowy, im bardziej dokładnie próbujemy określić jedną z tych dwóch rzeczy (pozycję lub pęd), tym bardziej niepewna staje się nasza wiedza na temat drugiej. To nie jest wina naszej technologii pomiarowej, ale fundamentalne ograniczenie natury kwantowej cząstek.

---

# Zasada nieoznaczoności Heisenberga cd.

W skrócie zasada nieoznaczoności mówi nam, że istnieje pewne zamieszanie, czyli niepewność związana z jednoczesnym pomiarowaniem niektórych właściwości cząstek, i nie ma możliwości całkowitego wyeliminowania tego zamieszania.

Tę zasadę opisuje wzór:

[//]: # (Tutaj szybkie opisanie wzoru)
$$

\Delta x\Delta p_{x}\geq \dfrac{\hbar }{2}

$$

[//]: # (tutaj żart)

[//]: # (
    Heisenberg jedzie samochodem i zatrzymuje go policja. 
    Policjant pyta się go: "Wie Pan ile Pan jechał?", 
    na co ten odpowiada: "Nie, ale za to przynajmniej wiem gdzie jestem"
)

---

# Splątanie kwantowe

Zjawisko splątania kwantowego to rodzaj powiązania między cząstkami w małej skali. Kiedy dwie cząstki zostaną splątane, ich stany kwantowe stają się wzajemnie zależne, nawet jeśli są od siebie oddzielone na duże odległości.

Co to oznacza? Jeśli wykonasz pomiar na jednej z tych splątanych cząstek, to natychmiast zdeterminuje on stan drugiej cząstki, bez względu na to, jak daleko się od siebie znajdują. To zdumiewające, ponieważ sugeruje, że informacja przemieszcza się między cząstkami szybciej niż światło, co jest sprzeczne z intuicją klasycznej fizyki.

Einstein nazwał to upiornym działaniem na odległość, ponieważ wydawało mu się to niematerialne i nieintuicyjne. Jednak eksperymenty potwierdzające splątanie kwantowe były wielokrotnie przeprowadzane i potwierdzają, że jest to rzeczywiste zjawisko w świecie kwantowym.

[//]: # (Tutaj żart o splątaniu kwantowym xd)
[//]: # (
    Nie jest tak ciężko zrozumieć na czym polega splątanie. Przedstawie przykład:
    Skarpety są w parach. Jeśli założysz jedną na swoją lewą stopę, 
    to natychmiast ta druga stanie się prawą skarpetką, 
    nie ważne gdzie we wszechświecie jest
)

---

# Co to jest Szyfrowanie Kwantowe?

Szyfrowanie kwantowe to zaawansowana forma bezpiecznej komunikacji, która wykorzystuje zasady fizyki kwantowej, aby zabezpieczyć przesyłane informacje. Głównym celem jest ochrona informacji przed przechwyceniem i nieautoryzowanym dostępem, nawet przez potężne komputery, które mogą próbować złamać tradycyjne metody szyfrowania.

Szyfrowanie kwantowe wykorzystuje unikalne właściwości mikroświata kwantowego do utworzenia bezpiecznego kanału komunikacyjnego. Pomimo obecnych wyzwań technologicznych i praktycznych, taka forma szyfrowania ma potencjał zrewolucjonizowania dziedziny bezpieczeństwa komunikacji.

---

# Zastosowania i Problemy:

- **Kwantowa dystrybucja klucza (QKD)**
- **Model ograniczonego i zakłóconego przechowywania kwantowego**
- **Kryptografia kwantowa niezależna od urządzenia**

---

# Kwantowa dystrybucja klucza (QKD)

Kwantowa dystrybucja klucza (QKD) to zaawansowana metoda bezpiecznego przesyłania tajnych kluczy do szyfrowania informacji między dwoma stronami. Podstawowym celem QKD jest umożliwienie dwóm stronom komunikacji ustalenia tajnego klucza w sposób, który jest odporny na przechwycenie przez potencjalnego przeciwnika.

Proces QKD wykorzystuje zasady fizyki kwantowej, takie jak zasada nieoznaczoności Heisenberga i splątanie kwantowe.

---

# Kwantowa dystrybucja klucza (QKD)

Oto ogólny sposób działania QKD w prostych słowach:

1. **Przygotowanie klucza**

[//]: # (Strony komunikacji używają specjalnych cząsteczek kwantowych na przykład fotony do stworzenia tajnego klucza. Te cząsteczki są przygotowywane w sposób, który wykorzystuje zasady kwantowej fizyki, co sprawia, że próby nieuprawnionego dostępu do klucza są łatwe do zauważenia.)

2. **Przesyłanie kwantowe** 

[//]: # (Przygotowane cząsteczki, zazwyczaj fotony, są wysyłane między dwoma stronami komunikacji. W tym procesie wykorzystuje się zasady nieoznaczoności Heisenberga i splątanie kwantowe, aby zabezpieczyć klucz przed potencjalnym przechwyceniem.)

3. **Monitorowanie bezpieczeństwa** 

[//]: # (Obie strony monitorują transmisję kwantową. Jeśli ktokolwiek próbuje przechwycić lub zmienić przesyłane cząsteczki, zasady kwantowe fizyki spowodują zmiany, które można wykryć.)

4. **Ustalanie klucza** 

[//]: # (Po przesłaniu cząsteczek obie strony porównują swoje wyniki i odrzucają ewentualne próby ingerencji. To, co pozostaje, staje się tajnym kluczem, który może być używany do szyfrowania i deszyfrowania komunikacji.)

[//]: # (Kwantowa dystrybucja klucza zapewnia bardzo silne zabezpieczenie, ponieważ ewentualne próby przechwycenia klucza są łatwo dostrzegalne. To sprawia, że QKD jest potencjalnie bardziej bezpieczne niż tradycyjne metody szyfrowania, które mogą być podatne na zaawansowane ataki komputerowe.)

---

# Model ograniczonego i zakłóconego przechowywania kwantowego

Model ograniczonego i zakłóconego przechowywania kwantowego mówi nam, że w praktyce przechowywanie informacji w systemach kwantowych jest ograniczone, a także podatne na zakłócenia czyli niepewności wynikające z oddziaływań z otoczeniem. Oznacza to, że utrzymanie dokładnych i długotrwałych kwantowych informacji jest trudne z powodu różnych czynników, takich jak fluktuacje środowiska, które mogą wprowadzać błędy i utratę informacji.

---

# Wyzwania:

- **Zasięg:** Komunikacja kwantowa na dużą skalę jest trudna do realizacji z powodu strat sygnału kwantowego (znanych
  jako dekoherencja) w kanałach transmisyjnych, takich jak światłowody.

- **Technologia:** Technologia kwantowa jest wciąż w fazie rozwoju, z wieloma wyzwaniami technicznymi i naukowymi do
  przezwyciężenia.

- **Koszt:** Obecne systemy kwantowe są kosztowne i zazwyczaj wymagają warunków pracy w niskich temperaturach lub
  próżni, co komplikuje ich wdrożenie na dużą skalę.

---

# Podsumowanie:

Szyfrowanie kwantowe oferuje obiecującą ścieżkę do bezpieczeństwa informacji w erze komputacji kwantowej. Chociaż
technologia ta jest wciąż w fazie rozwoju, jej zdolność do zapewnienia bezpieczeństwa komunikacji jest niezrównana w
porównaniu z klasyczną kryptografią.

---

# Żródła

[Wikipedia - https://en.wikipedia.org/wiki/Quantum_cryptography](https://en.wikipedia.org/wiki/Quantum_cryptography)

---

# Dziekujemy za uwage :3

- Szymon Jacoń
- Szymon Kaszuba-Gałka
