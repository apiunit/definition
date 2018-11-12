# VodaPi
The definition of vodapi


## Example config file
[vodapi](vodapi.yaml)

## Documentation
[documentation](DOC.md)


## Wersjonowanie API
Za pomoca definicji pliki yaml w formacie zdefiniowanym przez obecny standard vodapi:

version.vodapi.com

 
## Definiowanie i konfigurowanie srodowiska dla zespolu w firme poprzez VodaPI

Definicja zawiera Dane odnosnie srodowiska dla kwestii nietechniczynych, niemozliwych do zmiany poporzez skrypt.

VodaPi definiuje srodowisko zespolu, gdy potrzebne jest zdefiniowanie jakiego standardu obowiazujacego w trakcie procesu wytwarzania oprogramowania.

VodaPI jest dokumentacja dotyczaca wszystkich spraw koniecznych do realizacji zadan zespolu i wyjasniania sporow, wynikajacych z braku czasu, aby  nie doposcic do niskiej swiadomosci i nieskiej jakosci produkowanego kodu.

VodaPi poprawia komunikacje, dzieki definiowanie scislych zasad obowiazujacych w trakcie funkcjonowania zespolu.

Warto przeprowadzic symulacje praktyczna po definicji tych standardow:

## Przyklad 
praca programisty, praca z kodem.
![graph](https://vodapi.com/wp-content/uploads/2018/11/zenuml-5.png)


// https://docs.zenuml.com/


  @Starter(Developer)
  Code.writing()
  {
    if("Code is Valid") {
      Repository.commit
    }
  }


## Obsluga kodu
![graph](https://vodapi.com/wp-content/uploads/2018/11/zenuml-7.png)

  @Starter(Code)

  Local.commit() {
      CodeReview.verify() {      
        Remote.push() {            
            Production.update(){
              Remote.downgrade()
            }
        }
     }  
  }


## Apicra

Zalecanym zestawem standardow dla zdefiniowania i stworzenia architektury aplikacji jest apicra, ktory jest przy okazji naturalnym zapisem procesow, oraz ich dokumentacja.

Apicra definiuje architekture kazdego technicznego elementu systemu.

Apicra bazuje na wzorcach i architekturach, ktore funkcjonuja ponad jezykami. np model MVC.

Dzieki czemu latwe jest stworzenie zmian migration, np update/downgrade.

Apicra zawiera definicje architektury aplikacji, dzieki czemu mozliwe jest klarowne zdefiniowanie, kodu oraz bazy danych w dowolnym jezyku programowania, dzieki kreatorom kodu, generatorom zapytan oraz klas, obiektow.

Apicra definiuje aplikacje definiowanym przez rozne rozwiazania techniczne, gdzie jest lista skryptow jakie maja byc uzywane podczas uzywania aplikacji od strony dewelopera podczas testowania, wydawania aplikacji produkcyjnej i testowej.
