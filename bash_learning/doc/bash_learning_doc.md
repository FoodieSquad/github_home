# Bash Learning Note
## 基础
  * echo介绍
    - 输出字符串为双引号时会解析变量，无引号时也会解析变量
    - 当为单引号时，不会解析变量
    - 当需要解析转义字符时，需要用单引号或双引号包围字符串
      echo -e "1\t2\t" 或 echo -e '1\t2\t'

  * 