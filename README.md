# БытМаст

 в файле "ReadMi.docx" скрины программы


========================
Задание

----------------------

1С_Мастерская_Ремонт_Быт_Техники / 1s_master_remont_byt_technics
(В задании указаны минимально необходимые объекты, любое расширение состава объектов приветствуется)

Вам предлагается начать работу по автоматизации деятельности центра бытового обслуживания, который занимается оказанием различных услуг населению. В организацию обращаются клиенты, которые желают починить какую-либо бытовую технику.
 К тому же, организация продает (и, естественно, покупает) материалы – функциональность учета материалов и учета продаж так же нужно реализовать в системе.
В частности, вам нужно реализовать следующие возможности:
1.	Создать подсистемы, которые позволят логически разделить итоговую конфигурацию на части: оказание услуг, учет работы мастеров, учет материалов, а также сформировать интерфейс конфигурации.
2.	Создать общий реквизит Комментарий, который нужно будет использовать в документах.
3.	Разработать систему справочников, обеспечивающих функционирование системы. Там, где это повышает удобство работы со справочником, предусмотреть автоматизацию процесса заполнения. В частности, предполагается, что система будет иметь следующие справочники:
a)	Должности – для ведения списка должностей организации;
b)	Сотрудники – для ведения списка сотрудников, причем, сотрудников нужно разделить по должностям;
c)	Контрагенты – для ведения списка контрагентов (поставщиков и клиентов, в данном случае– юридических и физических лиц);
d)	Номенклатура – для хранения информации об услугах, которые предоставляет организация, о материалах, которые используются для ремонта.
4.	Разработать документ ПоступлениеМатериалов, он должен формировать движения по регистру ОстаткиМатериалов
5.	 Разработать документ РеализацияМатериалов. Он должен формировать движения по регистрам ОстаткиМатериалов и Продажи. Предусмотреть контроль остатков материалов при реализации.
6.	Разработать документ ПередачаМатериалов мастеру. Он должен формировать движения по регистрам ОстаткиМатериалов. Предусмотреть контроль остатков материалов при передаче.
7.	Разработать документ ОказаниеУслуги. Он должен формировать движения по регистру и ПродажиУслуг.   
8.	Создать регистр накопления ПродажиУслуг (вид – обороты) – в этом регистре планируется хранить сведения по оказанным услугам в денежном выражении другим организациям и физическим лицам.
9.	Создать Регистр сведений Цены для хранения цен на услуги и материалы (Запись в регистр вручную т.е. регистр независимый, периодический)
10.	Создать регистр накопления ОстаткиМатериалов (вид – остатки) – его планируется использовать для хранения сведений по остаткам материалов.
11.	Создать регистр накопления Продажи (вид – обороты) – в этом регистре планируется хранить сведения по реализации материалов другим организациям и физическим лицам.
12.	Заполнить информационную базу данными.
13.	Создать отчет Материалы – он должен содержать сведения об остатках, приходе и расходе материалов
14.	Создать отчет ПродажиПоКонтрагентам – он должен выводить показатель прибыли и количество единиц проданных материалов по контрагентам.
15.	Создать Отчет РейтингУслуг—он должен выводить информацию о том какие услуги принесли нашему предприятию наибольшую прибыль.
16.	Создать отчет в виде диаграммы ВыручкаМастеров- он должен показывать информацию о работе мастеров.
