git fetch test file

fetch : just check remote diff, download history to local 

git diff HEAD origin/master // local <> remote  
git log --decorate --all --oneline  // show diff-commit logs

선확인 후병합을 하기 위해 2단계로 분리하는것임
1.안전하고
2.병합을 여러가지로 할 수 있다. 


pull : fetch + merge (to local)

