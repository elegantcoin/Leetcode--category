## `Leetcode`-分类刷
`Jupyter`版本

<p align="center">
    <a href="https://github.com/elegantcoin/Leetcode--category"><img src="https://img.shields.io/badge/status-updating-brightgreen.svg"></a>
    <a href="https://github.com/python/cpython"><img src="https://img.shields.io/badge/Python-3.7-FF1493.svg"></a>
    <a href="https://github.com/elegantcoin/Leetcode--category"><img src="https://img.shields.io/badge/platform-Windows%7CLinux%7CmacOS-660066.svg"></a>
    <a href="https://opensource.org/licenses/mit-license.php"><img src="https://badges.frapsoft.com/os/mit/mit.svg"></a>
    <a href="https://github.com/elegantcoin/Leetcode--category/stargazers"><img src="https://img.shields.io/github/stars/elegantcoin/Leetcode--category.svg?logo=github"></a>
    <a href="https://github.com/elegantcoin/Leetcode--category/network/members"><img src="https://img.shields.io/github/forks/elegantcoin/Leetcode--category.svg?color=blue&logo=github"></a>
    <a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>
</p>
<br />

# [`Leetcode` 所有题目 以及数据详见](https://github.com/elegantcoin/All_Leetcode_Q_20190610)

- 根据[cspiration 大佬](https://cspiration.com/leetcodeClassification)的整理分类刷题,对`Leetcode`题目进行了分类排序;
- 根据[LiYu Lu 大佬](https://github.com/luliyucoordinate/Leetcode) 提供的答案，整理了题目答案的`Jupyter`。

## 方便刷题，如侵删
## 
  # - 实现过程是：
  - `bat`将多个`.py`合并为一个(`echo`增加分隔符，方便阅读区分，更方便后续处理);
  - 利用`excel VBA`将`Jupyter`需要的`Cell`格式进行调整:
    - 对"以及\进行转义;(注意缩进的处理)
    - 增加引号和换行符 {} [] 对;
    - 可以利用`echo`的分隔符进行标记，然后识别标记，在对应的地方增加行;
    - 增加`Jupyter`所需要的  ` "cell_type":` `"code", ``"execution_count": null,` `"metadata": {},` `"outputs": [],` `"source": [;`
    - 特别留意转义符;
    - 推荐插件 `Able`;
    
  - 利用[`JSONLint`](https://jsonlint.com/)的校验，确保无误;
  - 大功告成。
———————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————

  # - 思考：
  - 全部用`bat`能否实现?
  - `Python`实现?应该比较容易，主要涉及转义符和各个操作之间的逻辑先后顺序 比如文件内部本身的空格，引号，和\
  - 空格出现问题，可以用`VS Code`打开`.ipynb`文件，利用查找替换、正则表达式校验。
