# Branching Report

## Merge Statistics
- Total number of merges: [5]
- Fast-forward merges: [1]
- 3-way merges: [2]
- Merges with conflicts: [2]

## Branch History
```
*   03b06b3 (HEAD -> main, origin/main) Merge branch 'documentation'
|\  
| * 90e3e4d (documentation) Update documentation
|/  
*   77660c0 Merge feature/header-update with conflict resolution
|\  
| * 0d95666 Update header to v2.0
* | 7f932ed Customize blog title
|/  
*   920e4ac Merge branch 'feature/design'
|\  
| * 37c581f Improve design and add navigation
* | 54a81a7 Add comments section
|/  
* 3db042c Add posts page and functionality
* 06c95ad Initial project setup
```
## Lessons Learned
Ветвиться можно не только через создание (git branch "branch name") + переключение (git checkout "branch name"), а проще, через git switch -c. Узнал как устранять конфликты, как через CLI, а также и через VSCode интерактивно.