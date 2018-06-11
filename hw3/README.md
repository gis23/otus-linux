### Работа с LVM
#### Задание №3

Работа выполняется на имеющемся образе `otus-linux`, используется  `VagrantFile`

Нужно:
- уменьшить том под / до 8G
- выделить том под /home. /home - сделать том для снэпшотов
- выделить том под /var. /var - сделать в mirror

прописать монтирование в fstab
попробовать с разными опциями и разными файловыми системами ( на выбор)
- сгенерить файлы в /home/
- снять снэпшот
- удалить часть файлов
- восстановится со снэпшота
- залоггировать работу можно с помощью утилиты screen

* на нашей куче дисков попробовать поставить btrfs/zfs - с кешем, снэпшотами - разметить здесь каталог /opt

#### Выполнение
в файле `work.log` - журнал выполненых команд.