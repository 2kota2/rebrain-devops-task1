# GIT 12: Перенос коммитов с помощью cherry-pick

## Описание:
Иногда (очень редко) возникает необходимость применить в текущей ветке какой-либо конкретный коммит из истории. К примеру, у вас есть две ветки: master и develop. В develop находится множество коммитов, относящихся к разным элементам системы, и в данный момент вы не желаете мержить в master все изменения , но при этом хотите влить в эту ветку изменения, касающиеся определенной функциональности.

## Полезные ссылки:
[Сопровождение распределенных проектов](https://git-scm.com/book/ru/v2/%D0%A0%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-Git-%D0%A1%D0%BE%D0%BF%D1%80%D0%BE%D0%B2%D0%BE%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)

## Задание:
1. Клонируйте репозиторий: [git-cherry-pick](https://gitlab.rebrainme.com/rebrainme-devops/git-cherry-pick).
2. Переместите коммит **"Formatted code"** в ветку *master*.
3. Создайте репозиторий в своем аккаунте и залейте туда получившийся репозиторий.
4. Пришлите в ответе ссылку на ваш репозиторий.