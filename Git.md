# Git

## База
```bash
git status                       # что происходит
git log --oneline --graph --all  # красивая история
git diff                         # несохранённые изменения
```

## Ветки
```bash
git switch -c feature/x          # создать и перейти
git switch main                  # перейти
git branch -d feature/x          # удалить локально
```

## Откаты
```bash
git restore file.txt             # отменить изменения в файле
git reset --soft HEAD~1          # отменить коммит, оставить изменения
git revert <sha>                 # отменить коммит новым коммитом
```

## Аварийные ситуации
```bash
git reflog                       # история всех перемещений HEAD
git reset --hard HEAD@{2}        # вернуться назад
```
