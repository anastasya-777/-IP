# -IP

## "IP-адресация" 
### Отличия белого IP-адреса от серого IP-адреса:

#### Все IP-адреса протокола IPv4 делятся на публичные/глобальные/внешние (их называют "белые") — они используются в сети Интернет, и частные/локальные/внутренние (их называют "серые") — используются в локальной сети.

#### "Белые"(публичные) IP-адреса общаются только в глобальной сети интернет, но в то же время невозможно выдать каждому человеку уникальный белый IP-адрес.
#### "Серые"(частные) IP-адреса между собой общаются только в пределах одной локальной сети. Адреса в разных локальных сетях могут повторяться, и это не приведет к ошибкам. 
- Использование локальных позволяет меньше тратить публичные адреса. Они являются ограниченным ресурсом, так как устройств в мире огромное количество, и задать каждому уникальный номер невозможно. Использование серых айпишников позволяет увеличить количество устройств, подключенных к сети, при этом не затрачивая публичные.
-  Серые обеспечивают дополнительный уровень безопасности. Поскольку они не маршрутизируются напрямую через Интернет и не доступны извне локальной сети, это создает естественный барьер для защиты внутренних устройств от нежелательных соединений и вторжений. Организации могут использовать сетевые механизмы, такие как Network Address Translation (NAT), чтобы преобразовывать локальные IP в публичные при соединении с внешней сетью.
  
## "Что такое IP"

### Internet Protocol (IP, досл. «межсетевой протокол») — маршрутизируемый протокол сетевого уровня стека TCP/IP. Именно IP стал тем протоколом, который объединил отдельные компьютерные сети во всемирную сеть Интернет. Неотъемлемой частью протокола является адресация сети.

### Свойства:
#### IP объединяет сегменты сети в единую сеть, обеспечивая доставку пакетов данных между любыми узлами сети через произвольное число промежуточных узлов (маршрутизаторов). Он классифицируется как протокол сетевого уровня по сетевой модели OSI. IP не гарантирует надежной доставки пакета до адресата — в частности, пакеты могут прийти не в том порядке, в котором были отправлены, продублироваться (приходят две копии одного пакета), оказаться поврежденными (обычно повреждённые пакеты уничтожаются) или не прийти вовсе. Гарантию безошибочной доставки пакетов дают некоторые протоколы более высокого уровня — транспортного уровня сетевой модели OSI — например, TCP, которые используют IP в качестве транспорта.

## "Функции протокола IP"
#### Функции протокола IP определены в стандарте RFC-791 следующим образом: “Протокол IP” обеспечивает передачу блоков данных, называемых дейтаграммами, от отправителя к получателям, где отправители и получатели являются компьютерами, идентифицируемыми адресами фиксированной длины (IP-адресами).
#### Основные функции протокола IP. Основу транспортных средств стека протоколов TCP/IP составляет протокол межсетевого взаимодействия (Internet Protocol, IP). Он обеспечивает передачу дейтаграмм от отправителя к получателям через объединенную систему компьютерных сетей.
#### Функции реализуемые IP:
- Основа передачи данных.
- Адресация.
- Маршрутизация.
- Фрагментация дейтаграмм.
