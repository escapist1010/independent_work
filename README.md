# independent_work
pwd			Показать текущую рабочую директорию
			(папку, из которой выполняется
			команда).

ls			Отобразить файлы и папки в текущей
			директории.

l			-a Отобразить файлы и папки в текущей
			директории, в том числе скрытые.

cd first-project 	Перейти в папку first-project .

cd first-project/test 	Перейти в папку test внутри папки
			first-project .

cd .. 			Перейти на уровень выше (в
			родительскую папку).

cd ~ 			Перейти в домашнюю папку (например
			/Users/practicum ).

mkdir second-project 	Создать папку second-project .

rm hello.txt 		Удалить файл hello.txt .

rmdir images 		Удалить папку images .

rm -r second-project 	Удалить папку second-project и всё её
			содержимое.

touch hello.txt 	Создать файл hello.txt в текущей
			папке.

touch hello.txt hello2.txt hello3.txt 		Создать несколько файлов ( hello.txt ,
						hello2.txt , hello3.txt ).

echo <текст> 		Вывести текст на экран, например, echo
			"Hello, Practicum!"

echo <текст> >> <файл> 	Вывести текст в файл, например, echo
			"Hello, Practicum!" >> output.txt .

cat practicum.txt 	Вывести содержимое файла
			practicum.txt на экран.

cp helloPracticum.txt practicum.txt
						Копировать файлы и папки.
						В этом примере информация из
						источника
						helloPracticum.txt скопируется в
						назначение practicum.txt

mv <источник> <назначение> 			Переместить/переименовать файлы и
						папки.

tail <файл> 		Показать последние строки файла.

history 		Показать историю введённых команд.

head <файл> 		Показать первые строки файла.

man <команда> 		Показать руководство по команде.

clear 			Очистить экран терминала.

rm -rf. ~/Library/Developer/Xcode/DerivedData	Удалить папку DerivedData