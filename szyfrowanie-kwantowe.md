---
marp: true
theme: default
class: invert
size: 16:9
math: mathjax
---

# Szyfrowanie Kwantowe

---

<!-- @TODO: Szymon Jacon -->

# Co to są kwanty? Co to są kubity?

**Bit** - to najmniejsza jednostka informacji w informatyce _klasycznej_. Przyjmuje wartości $0$ albo $1$.

**Kubit** - to najmniejsza jednostka informacji w informatyce _kwantowej_. Przyjmuje wartości pomiędzy superpozycją $(1, 0)$ a $(0, 1)$, a po pomiarze stanu kwantowego przyjmuje jedną z wartości $1$ lub $0$. Kubity można również łączyć poprzez splatanie kwantowe.

---

<!-- @TODO: Szymon Jacon -->

# Kluczowe pojęcia mechaniki kwantowej

1. **Superpozycja**
2. **Zasada nieoznaczoności Heisenberga**
3. **Splątanie kwantowe**

---

<!-- @TODO: Szymon Jacon -->

# Superpozycja

W mechanice kwantowej cząstki mogą istnieć w wielu stanach jednocześnie. To zjawisko, znane jako superpozycja, umożliwia kodowanie znacznie większej ilości informacji na pojedynczym kubicie (podstawowej jednostce informacji kwantowej) w porównaniu z bitami w klasycznym komputerze.

---

<!-- @TODO: Szymon Jacon -->

# Superpozycja c.d.

Kolokwialnie rzecz ujmując superpozycję, można przedstawić przy pomocy poniższego problemu:

> To jak kiedy próbujesz się zdecydować, czy chcesz jeść lody truskawkowe czy czekoladowe, i ktoś mówi, że możesz mieć
> trochę obu na raz. Dzięki temu komputery kwantowe mogą rozwiązywać trudne problemy szybciej niż zwykłe komputery, bo
> patrzą na wiele możliwości naraz, a nie tylko na jedną.

<!--
@TODO

ŻART

Są trzy rodzaje ludzi na świecie
Ci co rozumieją mechanikę kwantową
Ci co nie rozumieją mechaniki kwantowej
Oraz ci co jednoczenie rozumieją i nie rozumieją mechaniki kwantowej
-->

---

<!-- @TODO: Szymon Jacon -->

# Zasada nieoznaczoności Heisenberga

Zasada nieoznaczoności Heisenberga to pomysł w fizyce kwantowej, który mówi nam, że istnieje pewne naturalne ograniczenie dotyczące tego, jak dokładnie możemy jednocześnie zmierzyć pewne właściwości cząstki. Konkretnie chodzi o pozycję i pęd cząstki.

Jeśli bardzo precyzyjnie zmierzymy pozycję cząstki, to nasza pewność co do jej pędu stanie się mniej precyzyjna, i odwrotnie. Innymi słowy, im bardziej dokładnie próbujemy określić jedną z tych dwóch rzeczy (pozycję lub pęd), tym bardziej niepewna staje się nasza wiedza na temat drugiej. To nie jest wina naszej technologii pomiarowej, ale fundamentalne ograniczenie natury kwantowej cząstek.

---

<!-- @TODO: Szymon Jacon -->

# Zasada nieoznaczoności Heisenberga c.d.

W skrócie zasada nieoznaczoności mówi nam, że istnieje pewne zamieszanie, czyli niepewność związana z jednoczesnym pomiarowaniem niektórych właściwości cząstek, i nie ma możliwości całkowitego wyeliminowania tego zamieszania.

Tę zasadę opisuje wzór:

$$
\Delta{x}\Delta{p_{x}} \geq \dfrac{\hbar}{2}
$$

<!--
@TODO

ŻART

Heisenberg jedzie samochodem i zatrzymuje go policja.
Policjant pyta się go: "Wie Pan ile Pan jechał?",
na co ten odpowiada: "Nie, ale za to przynajmniej wiem gdzie jestem"

Wzor:
\Delta x - nieokreslonosc pomiaru polozenia
\Delta p_{x} - nieokreslonosc pomiaru polozenia

Metafora:
Robienie zdjecia obiektom w ruchu.

Otworzenie migawki na krotko pozwala nam powiedziec z duza dokladnoscia pozycje obiektu ale nie jestesmy z tego zdjecia wyciagnac informacji o dokladnej predkosci.

Otworzenie migawki na dlugo pozwala nam powiedziec z duza dokladnoscia predkosc pojazdu ale nie jestesmy z tego zdjecia wyciagnac informacji o dokladnej pozycji.
-->

---

<!-- @TODO: Szymon Jacon -->

# Splątanie kwantowe

Zjawisko splątania kwantowego to rodzaj powiązania między cząstkami w małej skali. Kiedy dwie cząstki zostaną splątane, ich stany kwantowe stają się wzajemnie zależne, nawet jeśli są od siebie oddzielone na duże odległości.

Co to oznacza? Jeśli wykonasz pomiar na jednej z tych splątanych cząstek, to natychmiast zdeterminuje on stan drugiej cząstki, bez względu na to, jak daleko się od siebie znajdują. To zdumiewające, ponieważ sugeruje, że informacja przemieszcza się między cząstkami szybciej niż światło, co jest sprzeczne z intuicją klasycznej fizyki.

---

<!-- @TODO: Szymon Jacon -->

# Splątanie kwantowe c.d.

Einstein nazwał to upiornym działaniem na odległość, ponieważ wydawało mu się to niematerialne i nieintuicyjne. Jednak eksperymenty potwierdzające splątanie kwantowe były wielokrotnie przeprowadzane i potwierdzają, że jest to rzeczywiste zjawisko w świecie kwantowym.

<!--
@TODO

Szymon Kaszuba-Galka - ZOSTAW MOJ ZART

ŻART

Nie jest tak ciężko zrozumieć na czym polega splątanie. Przedstawie przykład:
Skarpety są w parach. Jeśli założysz jedną na swoją lewą stopę,
to natychmiast ta druga stanie się prawą skarpetką,
nie ważne gdzie we wszechświecie jest
-->

---

<!-- @TODO: Szymon Kaszuba-Galka -->

# Co to jest Szyfrowanie Kwantowe?

Szyfrowanie kwantowe to zaawansowana forma bezpiecznej komunikacji, która wykorzystuje zasady fizyki kwantowej, aby zabezpieczyć przesyłane informacje. Głównym celem jest ochrona informacji przed przechwyceniem i nieautoryzowanym dostępem, nawet przez potężne komputery, które mogą próbować złamać tradycyjne metody szyfrowania.

Szyfrowanie kwantowe wykorzystuje unikalne właściwości mikroświata kwantowego do utworzenia bezpiecznego kanału komunikacyjnego. Pomimo obecnych wyzwań technologicznych i praktycznych, taka forma szyfrowania ma potencjał zrewolucjonizowania dziedziny bezpieczeństwa komunikacji.

---

<!-- @TODO: Szymon Jacon -->

# Zastosowania i problemy Szyfrowania Kwantowego

- **Kwantowa dystrybucja klucza (QKD)**
- **Model ograniczonego i zakłóconego przechowywania kwantowego**
- **Kryptografia kwantowa niezależna od urządzenia**

---

<!-- @TODO: Szymon Kaszuba-Galka -->

# Kwantowa Dystrybucja Klucza (QKD)

Kwantowa dystrybucja klucza (QKD - _Quantum Key Distribution_) to zaawansowana metoda bezpiecznego przesyłania tajnych kluczy do szyfrowania informacji między dwoma stronami. Podstawowym celem QKD jest umożliwienie dwóm stronom komunikacji ustalenia tajnego klucza w sposób, który jest odporny na przechwycenie przez potencjalnego przeciwnika.

Proces QKD wykorzystuje zasady fizyki kwantowej, takie jak zasada nieoznaczoności Heisenberga i splątanie kwantowe.

---

<!-- @TODO: Szymon Kaszuba-Galka -->

# Kwantowa Dystrybucja Klucza (QKD) c.d.

Oto ogólny sposób działania QKD w prostych słowach:

1. **Przygotowanie klucza**

<!--
@TODO

Strony komunikacji używają specjalnych cząsteczek kwantowych na przykład fotony do stworzenia tajnego klucza. Te cząsteczki są przygotowywane w sposób, który wykorzystuje zasady kwantowej fizyki, co sprawia, że próby nieuprawnionego dostępu do klucza są łatwe do zauważenia
-->

2. **Przesyłanie kwantowe**

<!--
@TODO

Przygotowane cząsteczki, zazwyczaj fotony, są wysyłane między dwoma stronami komunikacji. W tym procesie wykorzystuje się zasady nieoznaczoności Heisenberga i splątanie kwantowe, aby zabezpieczyć klucz przed potencjalnym przechwyceniem.
-->

3. **Monitorowanie bezpieczeństwa**

<!--
@TODO

Obie strony monitorują transmisję kwantową. Jeśli ktokolwiek próbuje przechwycić lub zmienić przesyłane cząsteczki, zasady kwantowe fizyki spowodują zmiany, które można wykryć.
-->

4. **Ustalanie klucza**

<!--
@TODO

Po przesłaniu cząsteczek obie strony porównują swoje wyniki i odrzucają ewentualne próby ingerencji. To, co pozostaje, staje się tajnym kluczem, który może być używany do szyfrowania i deszyfrowania komunikacji.

Kwantowa dystrybucja klucza zapewnia bardzo silne zabezpieczenie, ponieważ ewentualne próby przechwycenia klucza są łatwo dostrzegalne. To sprawia, że QKD jest potencjalnie bardziej bezpieczne niż tradycyjne metody szyfrowania, które mogą być podatne na zaawansowane ataki komputerowe.
-->

---

<!-- @TODO: Szymon Jacon -->

# Model ograniczonego i zakłóconego przechowywania kwantowego

Model ograniczonego i zakłóconego przechowywania kwantowego mówi nam, że w praktyce przechowywanie informacji w systemach kwantowych jest ograniczone, a także podatne na zakłócenia czyli niepewności wynikające z oddziaływań z otoczeniem. Oznacza to, że utrzymanie dokładnych i długotrwałych kwantowych informacji jest trudne z powodu różnych czynników, takich jak fluktuacje środowiska, które mogą wprowadzać błędy i utratę informacji.

---

<!-- @TODO: Szymon Jacon -->

# Wyzwania

- **Zasięg:** Komunikacja kwantowa na dużą skalę jest trudna do realizacji z powodu strat sygnału kwantowego (znanych jako dekoherencja) w kanałach transmisyjnych, takich jak światłowody.

- **Technologia:** Technologia kwantowa jest wciąż w fazie rozwoju, z wieloma wyzwaniami technicznymi i naukowymi do przezwyciężenia.

- **Koszt:** Obecne systemy kwantowe są kosztowne i zazwyczaj wymagają warunków pracy w niskich temperaturach lub próżni, co komplikuje ich wdrożenie na dużą skalę.

---

<!-- @TODO: Szymon Kaszuba-Gałka -->

# Przykład użycia (QKD)

Najbardziej znanym przykładem jest protokół **BB84**, opracowany przez Charlesa Bennetta i Gillesa Brassarda w 1984 roku.

1. **Wybór Bazy i Stanów Kwantowych**:

   - Nadawca (zwykle nazywany Alicją) generuje losowy ciąg bitów (np. $01011$).
   - Dla każdego bitu Alicja losowo wybiera jedną z dwóch baz kwantowych:
     - bazę prostokątną $(1)$
     - bazę diagonalną $(2)$

---

<!-- @TODO: Szymon Kaszuba-Gałka -->

# Przykład użycia (QKD) c.d.

$$
\begin{align}
  0 \text{ jako } |0\rangle \\
  1 \text{ jako } |1\rangle
\end{align}
\tag{1}
$$

$$
\begin{align}
  0 \text{ jako } |+\rangle &= \frac{|0\rangle + |1\rangle}{\sqrt{2}} \\
  1 \text{ jako } |-\rangle &= \frac{|0\rangle - |1\rangle}{\sqrt{2}}
\end{align}
\tag{2}
$$

<!--
@TODO

Stan ∣+⟩ jest tzw. stanem superpozycji. Stany odpowiadaja odpowiednio polaryzacjom |0⟩ (wertykalny), |1⟩ (horyzontalny), |-⟩ (-45 stopni), |+⟩ (+45 stopni)

Matematycznie, ∣+⟩ jest zapisywany jako średnia ważona - z równymi wagami - tych dwóch stanów

(Tylko dla |+⟩ i |-⟩) Dzielnik sqrt_2 jest potrzebny do 'normalizacji' stanu, co oznacza, że całkowite prawdopodobieństwo znalezienia cząstki w jednym z tych stanów musi być równe 1. W mechanice kwantowej suma kwadratów amplitud - w tym przypadku wag - musi równać się 1.
-->

---

<!-- @TODO: Szymon Kaszuba-Gałka -->

# Przykład użycia (QKD) c.d.

2. **Wysyłanie Stanów Kwantowych**:

   - Alicja wysyła fotony reprezentujące wybrane bity w wybranych bazach do odbiorcy (nazywanego Bobem).

3. **Detekcja przez Odbiorcę**:

   - Bob, nie znając wyboru bazy Alicji, losowo wybiera bazę dla każdego fotonu, który otrzymuje, i dokonuje pomiaru.

---

<!-- @TODO: Szymon Kaszuba-Gałka -->

# Przykład użycia (QKD) c.d.

4. **Porównanie Baz**:

   - Alicja i Bob porównują publicznie wybrane przez siebie bazy. Zachowują tylko te bity, dla których wybrali tę samą bazę. Pozostałe bity są odrzucane.

5. **Weryfikacja i Finalny Klucz**:
   - Aby sprawdzić, czy nie doszło do podsłuchu, Alicja i Bob mogą porównać część swoich bitów. Jeśli bity są identyczne, mogą być pewni, że klucz jest bezpieczny. Klucz ten może być następnie użyty do zaszyfrowania komunikacji za pomocą klasycznego szyfrowania symetrycznego.

---

<!-- @TODO: Szymon Kaszuba-Gałka -->

# Podsumowanie

Szyfrowanie kwantowe oferuje obiecującą ścieżkę do bezpieczeństwa informacji w erze komputacji kwantowej. Chociaż technologia ta jest wciąż w fazie rozwoju, jej zdolność do zapewnienia bezpieczeństwa komunikacji jest niezrównana w porównaniu z klasyczną kryptografią.

---

# Dziekujemy za uwage :3

- Szymon Jacoń
- Szymon Kaszuba-Gałka
