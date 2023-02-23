# KODLUYORUZ İLK REPO
---
Bu repo [ Kodluyoruz ](https://kodluyoruz.org) Front-End Eğitiminde Oluşturduğumuz ilk repo . İçerisinde bir adet README.md dosyası ,bir adet de index.html barındırıyor.Ayrıca css klasörünün içerisine bir adet style.css ve img klasörünün içerisine bir adet projeresmi.PNG dosyası barındırıyor.

Tüm Değişikliklerimi commitleyip tekrardan Github'a Pushladım.

***

## Installation
**git clone:** GitHup'ta  repo oluşturduktan sonra bilgisayarıma klonlamak için yeşil butonu tıklayıp klonlamak için kodu aldım. ordan aldığım kodu  Vİsual COde ile terminal kullanarak ,git clone komutunun yanına githup tan aldığım kodu yanına yapıştırıp repomu bilgisayrıma klonlamayı başardım.

```
git clone https://github.com/bilalimakin/kodluyoruzilkrepo.git
```
## Contributing

```
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git status
On branch master

No commits yet
Changes to be committed:
        new file:   kodluyoruzilkrepo

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)

PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git log
fatal: your current branch 'master' does not have any commits yet
+++ b/kodluyoruzilkrepo
@@ -1 +1 @@
-Subproject commit 1e8309ecdd8066e006e777d6ab19207dbe3c0455
+Subproject commit 1e8309ecdd8066e006e777d6ab19207dbe3c0455-dirty
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git commit -m "markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu."
[master (root-commit) 56d217a] markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu.
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git add .
[main 8dd68ff] oluşturulan ve değiştirilen dosylar kaydedildi.
 create mode 100644 Markdown
 create mode 100644 css/style.css
 create mode 100644 img/projeresmi.PNG
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> cd ..
PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> git commit -m "vscode adlı dosyamı commitledim "
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> git add kodluyoruzilkrepo
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> git diff
warning: Not a git repository. Use --no-index to compare two paths outside a working tree
usage: git diff --no-index [<options>] <path> <path>

Diff output format options
    -p, --patch           generate patch
    -s, --no-patch        suppress diff output
    -u                    generate patch
    -U, --unified[=<n>]   generate diffs with <n> lines context
    -W, --function-context
                          generate diffs with <n> lines context
    --raw                 generate the diff in raw format
    --patch-with-raw      synonym for '-p --raw'
    --patch-with-stat     synonym for '-p --stat'
    --numstat             machine friendly --stat
    --shortstat           output only the last line of --stat
    -X, --dirstat[=<param1,param2>...]
                          output the distribution of relative amount of changes for each sub-directory
    --cumulative          synonym for --dirstat=cumulative
    --dirstat-by-file[=<param1,param2>...]
                          synonym for --dirstat=files,param1,param2...
    --check               warn if changes introduce conflict markers or whitespace errors
    --summary             condensed summary such as creations, renames and mode changes
    --name-only           show only names of changed files
    --name-status         show only names and status of changed files
    --stat[=<width>[,<name-width>[,<count>]]]
                          generate diffstat
    --stat-width <width>  generate diffstat with a given width
    --stat-name-width <width>
                          generate diffstat with a given name width
    --stat-graph-width <width>
                          generate diffstat with a given graph width
    --stat-count <count>  generate diffstat with limited lines
    --compact-summary     generate compact summary in diffstat
    --binary              output a binary diff that can be applied
    --full-index          show full pre- and post-image object names on the "index" lines
    --color[=<when>]      show colored diff
    --ws-error-highlight <kind>
                          highlight whitespace errors in the 'context', 'old' or 'new' lines in the diff
    -z                    do not munge pathnames and use NULs as output field terminators in --raw or --numstat
    --abbrev[=<n>]        use <n> digits to display object names
    --src-prefix <prefix>
                          show the given source prefix instead of "a/"
    --dst-prefix <prefix>
                          show the given destination prefix instead of "b/"
    --line-prefix <prefix>
                          prepend an additional prefix to every line of output
    --no-prefix           do not show any source or destination prefix
    --inter-hunk-context <n>
                          show context between diff hunks up to the specified number of lines
    --output-indicator-new <char>
                          specify the character to indicate a new line instead of '+'
    --output-indicator-old <char>
                          specify the character to indicate an old line instead of '-'
    --output-indicator-context <char>
                          specify the character to indicate a context instead of ' '

Diff rename options
    -B, --break-rewrites[=<n>[/<m>]]
                          break complete rewrite changes into pairs of delete and create
    -M, --find-renames[=<n>]
                          detect renames
    -D, --irreversible-delete
                          omit the preimage for deletes
    -C, --find-copies[=<n>]
                          detect copies
    --find-copies-harder  use unmodified files as source to find copies
    --no-renames          disable rename detection
    --rename-empty        use empty blobs as rename source
    --follow              continue listing the history of a file beyond renames
    -l <n>                prevent rename/copy detection if the number of rename/copy targets exceeds given limit

Diff algorithm options
    --minimal             produce the smallest possible diff
    -w, --ignore-all-space
                          ignore whitespace when comparing lines
    -b, --ignore-space-change
                          ignore changes in amount of whitespace
    --ignore-space-at-eol
                          ignore changes in whitespace at EOL
    --ignore-cr-at-eol    ignore carrier-return at the end of line
    --ignore-blank-lines  ignore changes whose lines are all blank
    -I, --ignore-matching-lines <regex>
                          ignore changes whose all lines match <regex>
    --indent-heuristic    heuristic to shift diff hunk boundaries for easy reading
    --patience            generate diff using the "patience diff" algorithm
    --histogram           generate diff using the "histogram diff" algorithm
    --diff-algorithm <algorithm>
                          choose a diff algorithm
    --anchored <text>     generate diff using the "anchored diff" algorithm
    --word-diff[=<mode>]  show word diff, using <mode> to delimit changed words
    --word-diff-regex <regex>
                          use <regex> to decide what a word is
    --color-words[=<regex>]
                          equivalent to --word-diff=color --word-diff-regex=<regex>
    --color-moved[=<mode>]
                          moved lines of code are colored differently
    --color-moved-ws <mode>
                          how white spaces are ignored in --color-moved

Other diff options
    --relative[=<prefix>]
                          when run from subdir, exclude changes outside and show relative paths
    -a, --text            treat all files as text
    -R                    swap two inputs, reverse the diff
    --exit-code           exit with 1 if there were differences, 0 otherwise
    --quiet               disable all output of the program
    --ext-diff            allow an external diff helper to be executed
    --textconv            run external text conversion filters when comparing binary files
    --ignore-submodules[=<when>]
                          ignore changes to submodules in the diff generation
    --submodule[=<format>]
                          specify how differences in submodules are shown
    --ita-invisible-in-index
                          hide 'git add -N' entries from the index
    --ita-visible-in-index
                          treat 'git add -N' entries as real in the index
    -S <string>           look for differences that change the number of occurrences of the specified string
    -G <regex>            look for differences that change the number of occurrences of the specified regex
    --pickaxe-all         show all changes in the changeset with -S or -G
    --pickaxe-regex       treat <string> in -S as extended POSIX regular expression
    --rotate-to <path>    show the change in the specified path first
    --find-object <object-id>
    --diff-filter [(A|C|D|M|R|T|U|X|B)...[*]]
    --output <file>       output to a specific file
PS C:\Users\bilal\Desktop\ANNOYMYSH> git log
PS C:\Users\bilal\Desktop\ANNOYMYSH> git commit 
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> git commit -m "tüm değişiklikler kaydedildi"
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\bilal\Desktop\ANNOYMYSH> cd vscode
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd kodluyoruzilkrepo
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git status  
On branch main
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git diff
diff --git a/README.md b/README.md
index 47c0157..a20179d 100644
--- a/README.md
+++ b/README.md
@@ -1,6 +1,55 @@
 # kodluyoruzilkrepo
-Kodluyoruz Eğitim Kapsamında açtığım ilk repo
+---
+Bu repo [ Kodluyoruz ](https://kodluyoruz.org) Front-End Eğitiminde Oluşturduğumuz ilk repo . İçerisinde bir adet README.md dosyası ,bir adetset mark: ...skipping...
diff --git a/README.md b/README.md
index 47c0157..a20179d 100644
--- a/README.md
+++ b/README.md
@@ -1,6 +1,55 @@
 # kodluyoruzilkrepo
-Kodluyoruz Eğitim Kapsamında açtığım ilk repo
+---
+Bu repo [ Kodluyoruz ](https://kodluyoruz.org) Front-End Eğitiminde Oluşturduğumuz ilk repo . İçerisinde bir adet README.md dosyası ,bir adet de index.html barındırıyor.Ayrıca css klasörünün içerisine bir adet style.css ve img klasörünün içerisine bir adet projeresmi.PNG dosyası barındırıyor.

-## Insatalation
+Tüm Değişikliklerimi commitleyip tekrardan Github'a Pushladım.
+
+***
+
+## Installation
 **git clone:** GitHup'ta  repo oluşturduktan sonra bilgisayarıma klonlamak için yeşil butonu tıklayıp klonlamak için kodu aldım. ordan aldığım kodu  Vİsual COde ile terminal kullanarak ,git clone komutunun yanına githup tan aldığım kodu yanına yapıştırıp repomu bilgisayrıma klonlamayı başardım.

+```
+git clone https://github.com/bilalimakin/kodluyoruzilkrepo.git
+```
+## Contributing
+
+```
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git status
+On branch master
+
+No commits yet
+Changes to be committed:
+        new file:   kodluyoruzilkrepo
+
+Changes not staged for commit:
+  (use "git add <file>..." to update what will be committed)
+  (use "git restore <file>..." to discard changes in working directory)
+  (commit or discard the untracked or modified content in submodules)
+
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git log
+fatal: your current branch 'master' does not have any commits yet
++++ b/kodluyoruzilkrepo
+@@ -1 +1 @@
+-Subproject commit 1e8309ecdd8066e006e777d6ab19207dbe3c0455
++Subproject commit 1e8309ecdd8066e006e777d6ab19207dbe3c0455-dirty
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git commit -m "markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu."
+[master (root-commit) 56d217a] markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu.
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git add .
+[main 8dd68ff] oluşturulan ve değiştirilen dosylar kaydedildi.
+ create mode 100644 Markdown
+ create mode 100644 css/style.css
+ create mode 100644 img/projeresmi.PNG
+ create mode 100644 index.html
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
+fatal: not a git repository (or any of the parent directories): .git
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git commit -m "vscode adlı dosyamı commitledim "
+fatal: not a git repository (or any of the parent directories): .git
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add kodluyoruzilkrepo
+fatal: not a git repository (or any of the parent directories): .git
+PS C:\Users\bilal\Desktop\ANNOYMYSH>
+```
+
+
...skipping...
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
diff --git a/README.md b/README.md
index 47c0157..a20179d 100644
--- a/README.md
+++ b/README.md
@@ -1,6 +1,55 @@
 # kodluyoruzilkrepo
-Kodluyoruz Eğitim Kapsamında açtığım ilk repo
+---
+Bu repo [ Kodluyoruz ](https://kodluyoruz.org) Front-End Eğitiminde Oluşturduğumuz ilk repo . İçerisinde bir adet README.md dosyası ,bir adet de index.html barındırıyor.Ayrıca css klasörünün içerisine bir adet style.css ve img klasörünün içerisine bir adet projeresmi.PNG dosyası barındırıyor.

-## Insatalation
+Tüm Değişikliklerimi commitleyip tekrardan Github'a Pushladım.
+
+***
+
+## Installation
 **git clone:** GitHup'ta  repo oluşturduktan sonra bilgisayarıma klonlamak için yeşil butonu tıklayıp klonlamak için kodu aldım. ordan aldığım kodu  Vİsual COde ile terminal kullanarak ,git clone komutunun yanına githup tan aldığım kodu yanına yapıştırıp repomu bilgisayrıma klonlamayı başardım.

+```
+git clone https://github.com/bilalimakin/kodluyoruzilkrepo.git
+```
+## Contributing
+
+```
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git status
+On branch master
+
+No commits yet
+Changes to be committed:
+        new file:   kodluyoruzilkrepo
+
+Changes not staged for commit:
+  (use "git add <file>..." to update what will be committed)
+  (use "git restore <file>..." to discard changes in working directory)
+  (commit or discard the untracked or modified content in submodules)
+
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git log
+fatal: your current branch 'master' does not have any commits yet
++++ b/kodluyoruzilkrepo
+@@ -1 +1 @@
+-Subproject commit 1e8309ecdd8066e006e777d6ab19207dbe3c0455
++Subproject commit 1e8309ecdd8066e006e777d6ab19207dbe3c0455-dirty
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> git commit -m "markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu."
+[master (root-commit) 56d217a] markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu.
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git add .
+[main 8dd68ff] oluşturulan ve değiştirilen dosylar kaydedildi.
+ create mode 100644 Markdown
+ create mode 100644 css/style.css
+ create mode 100644 img/projeresmi.PNG
+ create mode 100644 index.html
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
+[master (root-commit) 56d217a] markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu.
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git add .
+[main 8dd68ff] oluşturulan ve değiştirilen dosylar kaydedildi.
+ create mode 100644 Markdown
+ create mode 100644 css/style.css
+ create mode 100644 img/projeresmi.PNG
+ create mode 100644 index.html
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd ..
set mark: ...skipping...
+[master (root-commit) 56d217a] markdown dosyası oluşturuldu ve index.html dosyası oluşturuldu.
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> git add .
+[main 8dd68ff] oluşturulan ve değiştirilen dosylar kaydedildi.
+ create mode 100644 Markdown
+ create mode 100644 css/style.css
+ create mode 100644 img/projeresmi.PNG
+ create mode 100644 index.html
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode\kodluyoruzilkrepo> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH\vscode> cd ..
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add .
+fatal: not a git repository (or any of the parent directories): .gits): .git                                                     dlı dosyamı commitledim "
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git commit -m "vscode as): .gitdlı dosyamı commitledim "                                    po
+fatal: not a git repository (or any of the parent directories): .gits): .git
+PS C:\Users\bilal\Desktop\ANNOYMYSH> git add kodluyoruzilkrepo
+fatal: not a git repository (or any of the parent directorie:
```


