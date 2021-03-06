## git commit

Когда ваш индекс находится в таком состоянии, как вам и хотелось, вы можете зафиксировать свои изменения.

При выполнении команды `git commit` изменения всех файлов, внесённые в индекс, переносятся в репозиторий. При создании коммита (или точки фиксации изменений) требуется указать сообщение. Сообщение должно быть кратким и информативным, желательно придерживаться правил и [«стандартных» слов](./commits_rules.md).

Параметр *-m* позволяет написать сообщение из командной строки. Пример:

```=bash
git commit -m "update images"
```