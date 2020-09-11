# VodaPi
The definition of vodapi


## Example config file
[vodapi](vodapi.yaml)

## Documentation
[documentation](DOC.md)


## Wersjonowanie API
Za pomoca definicji pliki yaml w formacie zdefiniowanym przez obecny standard vodapi:

version.vodapi.com

 
## Definiowanie i konfigurowanie srodowiska dla zespolu w firme poprzez APIUnit

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
