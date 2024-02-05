# WAHAT IS JS?
Js использует garbage collection - форма автоматического менеджмента памяти. Пытается освободить память, выделенную программой, но на которую больше не ссылаются. Не нужно контролировать память, в которой хранится переменная, все делается автоматом используя внутренние инструменты is. 

Js это динамический язык с динамическим типами данных. Всё переменные можно назначать и переназначать, любой переменной можно присвоить любой тип данных. 
- При написании кода к прмеру имени переменных используется Кемелкейс (firstName, greenLight и т.д.)

Где хранятся данные js? 
- Стек(Stack) 
- Куча(Heap) 

# КЛЮЧЕВЫЕ СЛОВА Keywords
- ; - заканчивается утверждение.
- // однострочный комментарий 
- /* */ многострочный комментарий.
- = присвоение 

- let - переменная с возможностью менять значение переменной далее. Пример: let firstbame = "Anton";
- abstract -
- arguments -
- await -
- boolean -
- break -
- byte -
- case -
- catch -
- char -
- class -
- const - переменная, которую невозможно изменить в дальнейшем, имеет постоянное значение. 

- continue -
- debugger -
- default -
- delete -
- do -
- double -
- else -
- enum -
- eval -
- export -
- extends -
- false -
- final -
- finally -
- float -
- for -
- function -
- goto -
- if -
- implements -
- import -
- in -
- instanceof -
- int -
- interface -
- long -
- native -
- new -
- null -
- package -
- private -
- protected -
- public -
- return -
- short -
- static -
- super -
- switch -
- synchronized -
- this -
- throw -
- throws -
- transient -
- true -
- try -
- typeof  -
- var - создаёт переменную, которую можно изменить(лучше не использовать, лучший заменитель let)
- void -
- volatile -
- while -
- with -
- yield - 

# МАТЕМАТИЧЕСКИЕ ОПЕРАТОРЫ
- + 

# ТИПЫ ДАННЫХ
- Primitive types: примитивы нельзя изменить, не имеют методов и свойств. А их данные хранятся в Стек памяти. Движок точно знает сколько памяти для них нужно выделить. Передаются в значении. Примечание, поскольку все переменные можно менять и переназначать, то если изменить значение примитива, то это уже будет новая ячейка памяти. 

- Boolean 
- Number
- BigInt
- String
- Symbol
- Null
- Undefined


- Objects: объекты изменяемы, их содержимое можно изменять без создания нового объекта. Объекты могут содержать набор свойств. Они передаются по ссылке и хранятся в а в куче heap. 

- Plain objects
- Functions
- Collection types (Array,map,set)
- Dates
- Class instances
- Errors
- Promises