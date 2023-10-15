# 30 основных команд  
---  


1. **git config --global user.name "Имя"** - задать имя  
**git config --global user.email "...@mail.."** - задать адрес электронной почты  
2. **git config --global credential.helper cache** - Кэширование учётных данных  
3. **git init** - Инициализация репозитория  
4. **git status** - Проверка статуса репозитория
5. **git commit -m "Your short summary about the commit"** - коммит (Внесение изменений однострочным сообщением)  
6. **git log** -  Просмотр истории коммитов  
7. **git commit --amend -m "Updated message for the previous commit"** - Изменение последнего коммита  
8. **git revert HEAD** - Откат последнего коммита
### Разница между **revert** и **reset**:  
```Команда **git revert** отменяет изменения,  
записанные только одним коммитом.  
Она не откатывает проект к более раннему состоянию,  
удаляя все последующие коммиты,  
как это делает команда **git reset**.
```  
9. **git branch new_branch_name** - Создание новой ветки  
**git checkout -b new_branch_name** - Создание новой ветки и переход в неё  
10. **git branch** - Просмотр списка веток  
**git branch -a** - вывести список удалённых веток с помощью флага ``` -a ```  
11. **git branch -d existing_branch_name** - Удаление ветки  
12. **git log --graph --oneline --decorate** - Отображение журнала фиксации в виде графика для текущей  
**git log --all --graph --oneline --decorate** - Для просмотра истории коммитов по всем веткам используется флаг ``` --all ```  
