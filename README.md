<!DOCTYPE html >
<html lang="en">
<голова>
    <мета шлако="UTF-8">
    <мета ім'я = "переклад" vmist = "ширина = ширина пристрой, початкова шкала = 1,0" >
    <назва>Сканер Штрих-коду</назва>
    <стиль>
 тило {
 симейство шрифтів: Аріал, sans-serif;
 текстовий знак: центр;
 marža-verh: 50pks;
        }
 .контер {
 Ширина: 300 шт. С;
 marža: 0 avto;
        }
 vhid [typ = "тексст"], vhid [tipp = "kiljkistj"] {
 ширина: 100%;
 прокладка: 10 шт;
 marža-dno: 20 шт;
 строзьмир шрифту: 16шт;
        }
 кнопка {
 прокладка: 10 шт. 20 шт;
 строзьмир шрифту: 16шт;
 курсор: вказівник;
 фоновій колер: # 4CAF50;
 колір: білій;
 kordonn: jodén;
 kordonn-radius: 4шт;
        }
 knopka: навігація {
 фоновій колер: # 45a049;
        }
    </стиль>
</голова>
<тило>
    <дів клас="контейнер">
        <бог2>Сканер Штрих-коду</бог2>
        <видид тип="текст" Ідентифікатор="productName" заповнювач="Назва тру"><бр>
        <видид тип="кілкість" Ідентифікатор="кілкість" заповнювач="Кілкість"><бр>
        <кнопка клацанна="addToogleSheet ()">ОК</кнопка>
    </дів>

    <сценарій >
     funkciia addToogleSheet () {
     var productName = document.getElementById ('productName');
     var kilkistöh = document.getElementById ('kilöhkisth');

     // URL-адреса Ваша-адреса від Google Apps Script
     var scriptUrl = "YOUR_GOOGLE_APPS_SCRIPT_URL_HERE";

     // Виконайте AJAX-запіт до Вашого Google Apps Script dlia dodavannia danihs
     var xhr = новий XMLHttpRequest ();
     xhr.open ("GET", scriptUrl + "?productName = "+ productName +" & kiljkistöh = "+ килькість, правда);
     xhr.send ();
        }
    < / skript >
< / тило >
</html>
