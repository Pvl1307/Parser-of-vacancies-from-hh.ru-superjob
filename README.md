# Job_Parser_CW4

## Описание
Программа получает информацию о вакансиях с платформ HeadHunter и SuperJob, сохраняет ее в файл и позволяет удобно работать с ней (добавлять и удалять вакансии, фильтровать по размеру зарплаты, выводить лучшие вакансии из списка).

## Установка

Для установки проекта и его зависимостей, выполните следующие шаги:

1. Склонируйте репозиторий на ваше устройство:
   git clone https://github.com/Pvl1307/Job_Parser_CW4.git
2. Перейдите в директорию проекта
3. Установите poetry и пропишите:
   poetry shell
   poetry intall

## Работа программы
Вам будут задаваться вопросы.

Будет задан вопрос, с какой платформы получить вакансии, по каким ключевым словам осуществить поиск и какое количество вакансий вывести. Вакансии выводятся по одной, и для каждой будет задан вопрос, добавлять ли ее в список желаемых или нет. Затем будет возможность продолжить поиск на той же платформе или на другой.

Далее необходимо ввести диапазон зарплат. Если в списке нет вакансий, соответствующих заданному диапазону, будет выведено соответствующее сообщение. Если такие вакансии имеются, будет предложено ввести количество вакансий ,которые Вы хотите увидеть. Если это число будет больше количества позиций в списке, будет выведен весь список.

Также есть возможность продолжить или завершить работу. При продолжении работы можно будет:

1) Вывести все отсортированные вакансии.
2) Удалить вакансию по ID
3) Произвести повторный поиск вакансий
4) Отсортировать еще раз(если Вы добавили еще вакансии или хотите отсортировать по новым значениям)

Для завершения работы нужно прописать "стоп", и программа будет завершена.
