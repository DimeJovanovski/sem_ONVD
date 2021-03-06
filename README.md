## Процесот на креација на веб-сајт

Изработил: Димитар Јовановски


## Содржина

Процесот на креација на веб-сајт
   - Основни факти за веб-сајтот
   - Прва секција
   - Втора секција
   - Трета, четврта и петта секција
   - Подножје (footer)
   - Мулти уред / крос платформно


### Основни факти за веб-сајтот
Наслов: „Димитар Јовановски“  
Темплејт: [Ziggy](https://www.free-css.com/free-css-templates/page244/ziggy)  
Фонт: font-family: "OracleSansVF", "OracleSansVFCyGr", - apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue ...  
Големина на фонт: 13px  
Основни тематички нијанси:

1. #7a7a7a
2. #232323
3. #ffffff

Бр. страници на сајтот: 1
Бр. на искористени слики: 18
Големина на HTML фајл: 9.73 KB
Бр. Редови на HTML фајл: 212
Вкупна големина на сите CSS фајлови: 341 KB
Крос платформи и уреди: да

### Прва секција

Покрај очигледните естетски промени, како што е промена на позадината за да одговара со тематиката... Во првата секција
беа направени и значајни структурни промени за да се оствари оригиналната идеа за изглед на сајтот:

1. Најпво, како претходно напоменато, беше променета позадината, за која беше поставена слика (наместо gradient /
    боја) која повеќе одговара со наведената тематика.
2. Оригинално, првата секција на темплејтот беше составена од _h2_ , _div_ и _span_ кои се сместени во _div_ наречен _„text-_
    _content“_. Сето ова мораше да се отстрани и на негово место да се изгради структура од _img_ во _div_ - от _„text-content“_.
3. За крај, со CSS да се стилизира сликата и _div_ - от т.ш. **динамично** самостојно ќе си ги променува димензиите, соодветно
    со големината на пребарувачот / уредот.


### Втора секција

Бидејќи за мојот проект се потребни три колони наместо четири, и овде мораше да се направат некои структурни промени:

1. Првиот чекор е очегледно, да се избрише една колона од колоните со класа _„col-md-3 col-sm- 6 “_ (кои, освен
    содржината во нив, се воглавно со исти карактеристики).
2. Затоа што помеѓу колоните маргината е 0, ширината на колоните се поставува на 33.3% за да го зафаќа целиот
    родител контејнер како што треба.
3. Нешто што го немаше во оригиналниот темплејт, но го додадов е линк кој води кон поширок дел (текст) кој се наоѓа
    на истата страница т.е. колоните се како еден вид интро и со кликање на нив, го води корисникот кон поширока
    содржина.
4. Последниот дел е естетскиот дел, каде се заменуваат сликите и се испишува нова содржина за нив.


### Трета, четврта и петта секција

Во овој дел промените се главно естетски:

1. Променета е позадината со нова слика со иста резолуција.
2. Исто така се променета левата слика, како и текстот.
3. На содржината (поточно текстот), за многу малку му е променета маргината за да биде по inline со сликата, како и
    други слични мали поместувања за да се постигне најдобриот изглед (на различни уреди).

_Петтата секција е скоро иста како претходните две. Разликата е тоа што сликата е од десно, а содржината од лево.
Ова е поради позадината која е како искосен исечок и за да се совпадне со посакуваниот изглед._


### Подножје (footer)

Кај подножјето, изгледот кој сакав да го постигнам е стандардна постава од хоризонтална листа со линкови кон социјални
мрежи, репозитури, др. страници и сл. Оригиналниот код од footer-от иако на прелистувач изгледаше скоро идентично како
со тој на проектов, сакав да изработам по проста / разбирлива варијанта која ќе ја врши истата работа.

1. Изработив листа од линкови чии дете елемент е слика ( 30 x30). Листата е поставена хоризонтално, без никаков
    дополнителен стајлинг.
2. За појасно да се гледаат сликите, меѓу елементите на низата е поставена маргина од 15px од лева и десна страна.
3. Над листата исто така е поставен е и header (h6) кој е центриран. А под истата е поставен центриран параграф во кој е
    наведен авторот на сајтот.

_Исто така за подобар естетски изглед сменета е и позадината на подножјето._


### Мулти уред / крос платформно

Едно од најбитните фактори на било кој веб-сајт денес е да може да се користи на различни уреди, под различни резолуции.
Затоа беше битно покрај избор на квалитетен темплејт, да се направат сооветни промени кои ќе го подобрат тоа онлајн
искуството. Иако со дотогашниот код елементите на страната соодветно менуваат димензии, потребно беше да се воведе и
_@media_ правило за одредени демензии како: 1200px, 992px, 970px, 550px, 545px... Сето ова со додатно уредување на
маргини и падинг и сл., воведува до финалниот изглед.


