3.	
Необходимо разработать элемент управления (пользовательский) для редактирования IPv4 адреса.
Элемент управления должен запрещать вводить текст, 
не являющийся корректным IP-адресом. 
Элемент управления должен быть удобным, как минимум, 
должна быть возможность перемещаться между разделами IP-адреса с помощью управляющих клавиш. 
Свойства IPAddress элемента управления должно быть типа System.Net.IPAddress (при необходимости реализуйте конвертер для данного типа).

При разработке любого элемента управления из списка ниже, кроме собственно разработки, необходимо с помощью атрибутов задать:
●	описания свойств и событий;
●	разделы в инспекторе свойств, в которых свойства и события помещаются;
●	значения по умолчанию для свойств;
●	свойство и событие по умолчанию;
●	свойства, доступные для привязки;
●	неотображаемые в инспекторе свойств свойства и события (если существует такая потребность);
●	конвертеры и редакторы для свойств (если существует такая потребность).