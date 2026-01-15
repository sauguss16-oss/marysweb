2026-01-14 20:00:04.643 [info] [main] Log level: Info
2026-01-14 20:00:04.643 [info] [main] Validating found git in: "/usr/local/bin/git"
2026-01-14 20:00:04.716 [info] [main] Using git "2.52.0" from "/usr/local/bin/git"
2026-01-14 20:00:04.716 [info] [Model][doInitialScan] Initial repository scan started
2026-01-14 20:00:04.863 [info] > git rev-parse --show-toplevel [56ms]
2026-01-14 20:00:05.442 [info] > git rev-parse --git-dir --git-common-dir --show-superproject-working-tree [570ms]
2026-01-14 20:00:05.509 [info] [Model][openRepository] Opened repository (path): /Users/mac
2026-01-14 20:00:05.509 [info] [Model][openRepository] Opened repository (real path): /Users/mac
2026-01-14 20:00:05.509 [info] [Model][openRepository] Opened repository (kind): repository
2026-01-14 20:00:05.518 [info] [Model][doInitialScan] Initial repository scan completed - repositories (1), closed repositories (0), parent repositories (0), unsafe repositories (0)
2026-01-14 20:00:06.060 [info] > git config --get commit.template [440ms]
2026-01-14 20:00:06.374 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [169ms]
2026-01-14 20:00:07.066 [info] > git fetch [1557ms]
2026-01-14 20:00:07.066 [info] remote: Repository not found.
fatal: repository 'https://github.com/marysfriedchicken0-dotcom/mac.git/' not found
2026-01-14 20:00:07.068 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [627ms] (cancelled)
2026-01-14 20:00:07.125 [info] > git status -z -uall [742ms] (cancelled)
2026-01-14 20:00:07.184 [info] > git config --get commit.template [58ms]
2026-01-14 20:00:07.184 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [111ms]
2026-01-14 20:00:07.218 [info] > git config --get --local branch.main.vscode-merge-base [28ms]
2026-01-14 20:00:07.218 [warning] [Git][config] git config failed: Failed to execute git
2026-01-14 20:00:07.234 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [25ms]
2026-01-14 20:00:07.282 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [41ms]
2026-01-14 20:00:07.296 [info] > git reflog main --grep-reflog=branch: Created from *. [73ms]
2026-01-14 20:00:07.353 [info] > git symbolic-ref --short refs/remotes/origin/HEAD [25ms]
2026-01-14 20:00:07.353 [info] fatal: ref refs/remotes/origin/HEAD is not a symbolic ref
2026-01-14 20:00:07.353 [warning] [Repository][getDefaultBranch] Failed to get default branch details: Failed to execute git.
2026-01-14 20:00:33.385 [info] > git status -z -uall [26147ms] (cancelled)
2026-01-14 20:00:33.708 [info] > git config --get commit.template [324ms]
2026-01-14 20:00:33.773 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [60ms]
2026-01-14 20:00:33.799 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [19ms]
2026-01-14 20:00:44.549 [info] > git status -z -uall [10773ms] (cancelled)
2026-01-14 20:03:19.127 [info] > git fetch [527ms]
2026-01-14 20:03:19.129 [info] remote: Repository not found.
fatal: repository 'https://github.com/marysfriedchicken0-dotcom/mac.git/' not found
2026-01-14 20:03:19.148 [info] > git config --get commit.template [15ms]
2026-01-14 20:03:19.149 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [14ms]
2026-01-14 20:03:19.170 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [16ms]
2026-01-14 20:03:28.480 [info] > git status -z -uall [9328ms] (cancelled)
2026-01-14 20:13:01.657 [info] > git check-ignore -v -z --stdin [44ms]
2026-01-14 20:13:02.614 [info] > git fetch [1461ms]
2026-01-14 20:13:02.614 [info] remote: Repository not found.
fatal: repository 'https://github.com/marysfriedchicken0-dotcom/mac.git/' not found
2026-01-14 20:13:02.637 [info] > git config --get commit.template [17ms]
2026-01-14 20:13:02.650 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [22ms]
2026-01-14 20:13:02.672 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [15ms]
2026-01-14 20:13:05.209 [info] > git check-ignore -v -z --stdin [215ms]
2026-01-14 20:13:05.870 [info] > git show --textconv :Desktop/imagenmarys/.github/copilot-instructions.md [34ms]
2026-01-14 20:13:05.879 [info] > git ls-files --stage -- Desktop/imagenmarys/.github/copilot-instructions.md [30ms]
2026-01-14 20:13:05.892 [info] > git hash-object -t tree /dev/null [18ms]
2026-01-14 20:13:05.892 [warning] [GitFileSystemProvider][readFile] File not found - git:/Users/mac/Desktop/imagenmarys/.github/copilot-instructions.md.git?%7B%22path%22%3A%22%2FUsers%2Fmac%2FDesktop%2Fimagenmarys%2F.github%2Fcopilot-instructions.md%22%2C%22ref%22%3A%22%22%7D
2026-01-14 20:13:05.896 [info] > git hash-object -t tree /dev/null [13ms]
2026-01-14 20:13:05.896 [warning] [GitFileSystemProvider][stat] File not found - git:/Users/mac/Desktop/imagenmarys/.github/copilot-instructions.md.git?%7B%22path%22%3A%22%2FUsers%2Fmac%2FDesktop%2Fimagenmarys%2F.github%2Fcopilot-instructions.md%22%2C%22ref%22%3A%22%22%7D
2026-01-14 20:13:15.507 [info] > git blame --root --incremental 74c98184ff399993c66b25b95dd4dca5b29ca4bf -- Desktop/imagenmarys/.github/copilot-instructions.md [49ms]
2026-01-14 20:13:15.509 [info] fatal: no such path Desktop/imagenmarys/.github/copilot-instructions.md in 74c98184ff399993c66b25b95dd4dca5b29ca4bf
2026-01-14 20:13:55.840 [info] > git status -z -uall [53186ms] (cancelled)
2026-01-14 20:13:56.816 [info] > git check-ignore -v -z --stdin [84ms]
2026-01-14 20:14:03.376 [info] > git check-ignore -v -z --stdin [105ms]
2026-01-14 20:14:07.607 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:14:09.397 [info] > git check-ignore -v -z --stdin [39ms]
2026-01-14 20:14:12.451 [info] > git check-ignore -v -z --stdin [21ms]
2026-01-14 20:14:12.856 [info] > git check-ignore -v -z --stdin [102ms]
2026-01-14 20:14:12.998 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:14:15.399 [info] > git check-ignore -v -z --stdin [19ms]
2026-01-14 20:14:15.767 [info] > git check-ignore -v -z --stdin [19ms]
2026-01-14 20:14:16.361 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:14:18.151 [info] > git check-ignore -v -z --stdin [26ms]
2026-01-14 20:14:27.077 [info] > git check-ignore -v -z --stdin [32ms]
2026-01-14 20:14:28.918 [info] > git check-ignore -v -z --stdin [26ms]
2026-01-14 20:14:29.267 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:14:29.795 [info] > git check-ignore -v -z --stdin [28ms]
2026-01-14 20:14:30.245 [info] > git check-ignore -v -z --stdin [28ms]
2026-01-14 20:14:32.396 [info] > git check-ignore -v -z --stdin [25ms]
2026-01-14 20:14:34.433 [info] > git check-ignore -v -z --stdin [31ms]
2026-01-14 20:14:34.906 [info] > git check-ignore -v -z --stdin [24ms]
2026-01-14 20:14:36.488 [info] > git check-ignore -v -z --stdin [19ms]
2026-01-14 20:14:43.137 [info] > git check-ignore -v -z --stdin [41ms]
2026-01-14 20:14:43.747 [info] > git check-ignore -v -z --stdin [34ms]
2026-01-14 20:14:45.437 [info] > git check-ignore -v -z --stdin [26ms]
2026-01-14 20:14:46.754 [info] > git check-ignore -v -z --stdin [53ms]
2026-01-14 20:14:47.053 [info] > git check-ignore -v -z --stdin [31ms]
2026-01-14 20:14:47.460 [info] > git check-ignore -v -z --stdin [26ms]
2026-01-14 20:14:48.797 [info] > git check-ignore -v -z --stdin [21ms]
2026-01-14 20:14:49.217 [info] > git check-ignore -v -z --stdin [30ms]
2026-01-14 20:14:49.827 [info] > git check-ignore -v -z --stdin [25ms]
2026-01-14 20:14:50.184 [info] > git check-ignore -v -z --stdin [28ms]
2026-01-14 20:14:50.675 [info] > git check-ignore -v -z --stdin [151ms]
2026-01-14 20:14:55.057 [info] > git check-ignore -v -z --stdin [38ms]
2026-01-14 20:14:56.225 [info] > git check-ignore -v -z --stdin [23ms]
2026-01-14 20:14:56.837 [info] > git check-ignore -v -z --stdin [28ms]
2026-01-14 20:14:57.083 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:14:58.823 [info] > git check-ignore -v -z --stdin [17ms]
2026-01-14 20:14:59.671 [info] > git check-ignore -v -z --stdin [11ms]
2026-01-14 20:15:00.922 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:15:01.271 [info] > git check-ignore -v -z --stdin [20ms]
2026-01-14 20:15:01.557 [info] > git check-ignore -v -z --stdin [22ms]
2026-01-14 20:15:02.619 [info] > git check-ignore -v -z --stdin [24ms]
2026-01-14 20:15:03.366 [info] > git check-ignore -v -z --stdin [55ms]
2026-01-14 20:15:03.553 [info] > git check-ignore -v -z --stdin [28ms]
2026-01-14 20:15:05.084 [info] > git check-ignore -v -z --stdin [35ms]
2026-01-14 20:15:05.319 [info] > git check-ignore -v -z --stdin [25ms]
2026-01-14 20:15:06.547 [info] > git check-ignore -v -z --stdin [109ms]
2026-01-14 20:15:07.072 [info] > git check-ignore -v -z --stdin [37ms]
2026-01-14 20:16:46.074 [info] > git fetch [608ms]
2026-01-14 20:16:46.076 [info] remote: Repository not found.
fatal: repository 'https://github.com/marysfriedchicken0-dotcom/mac.git/' not found
2026-01-14 20:16:46.101 [info] > git config --get commit.template [19ms]
2026-01-14 20:16:46.108 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [24ms]
2026-01-14 20:16:46.134 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [21ms]
2026-01-14 20:17:02.622 [info] > git status -z -uall [16512ms] (cancelled)
2026-01-14 20:17:04.135 [info] > git check-ignore -v -z --stdin [49ms]
2026-01-14 20:17:16.744 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [23ms]
2026-01-14 20:17:18.560 [info] > git check-ignore -v -z --stdin [56ms]
2026-01-14 20:17:19.267 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [24ms]
2026-01-14 20:17:20.423 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [25ms]
2026-01-14 20:17:23.875 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [51ms]
2026-01-14 20:17:28.979 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [33ms]
2026-01-14 20:17:31.000 [info] > git log --format=%H%n%aN%n%aE%n%at%n%ct%n%P%n%D%n%B -z --shortstat --diff-merges=first-parent -n50 --skip=0 --topo-order --decorate=full --stdin [40ms]
2026-01-14 20:17:37.586 [info] > git -c user.useConfigOnly=true commit --quiet [4036ms]
2026-01-14 20:17:37.586 [info] Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: no email was given and auto-detection is disabled
2026-01-14 20:17:37.605 [info] > git config --get-all user.name [17ms]
2026-01-14 20:17:37.626 [info] > git config --get commit.template [17ms]
2026-01-14 20:17:37.628 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [15ms]
2026-01-14 20:17:37.664 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [28ms]
2026-01-14 20:18:00.365 [info] > git status -z -uall [22734ms] (cancelled)
2026-01-14 20:18:02.189 [info] > git check-ignore -v -z --stdin [177ms]
2026-01-14 20:18:08.814 [info] > git -c user.useConfigOnly=true commit --quiet [114ms]
2026-01-14 20:18:08.815 [info] Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: no email was given and auto-detection is disabled
2026-01-14 20:18:08.850 [info] > git config --get-all user.name [31ms]
2026-01-14 20:18:08.870 [info] > git config --get commit.template [13ms]
2026-01-14 20:18:08.895 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [22ms]
2026-01-14 20:18:08.916 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [14ms]
2026-01-14 20:18:21.985 [info] > git status -z -uall [13087ms] (cancelled)
2026-01-14 20:18:34.024 [info] > git check-ignore -v -z --stdin [132ms]
2026-01-14 20:18:58.926 [info] > git -c user.useConfigOnly=true commit --quiet [209ms]
2026-01-14 20:18:58.926 [info] Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: no email was given and auto-detection is disabled
2026-01-14 20:18:58.948 [info] > git config --get-all user.name [17ms]
2026-01-14 20:18:58.975 [info] > git config --get commit.template [23ms]
2026-01-14 20:18:58.988 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [32ms]
2026-01-14 20:18:59.035 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [37ms]
2026-01-14 20:19:05.984 [info] > git check-ignore -v -z --stdin [43ms]
2026-01-14 20:19:30.856 [info] > git status -z -uall [31863ms] (cancelled)
2026-01-14 20:19:32.033 [info] > git check-ignore -v -z --stdin [119ms]
2026-01-14 20:19:58.415 [info] > git fetch [662ms]
2026-01-14 20:19:58.416 [info] remote: Repository not found.
fatal: repository 'https://github.com/marysfriedchicken0-dotcom/mac.git/' not found
2026-01-14 20:19:58.522 [info] > git config --get commit.template [98ms]
2026-01-14 20:19:58.561 [info] > git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) --ignore-case refs/heads/main refs/remotes/main [65ms]
2026-01-14 20:19:58.629 [info] > git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname) [28ms]
2026-01-14 20:19:59.990 [info] > git check-ignore -v -z --stdin [44ms]
2026-01-14 20:20:04.865 [info] > git check-ignore -v -z --stdin [92ms]
2026-01-14 20:20:27.510 [info] > git status -z -uall [28939ms] (cancelled)
