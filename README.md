# Leetcode-分类刷
Jupyter版本

<p align="center"><font color=red>[Leetcode 所有题目 以及数据详见](https://github.com/elegantcoin/All_Leetcode_Q_20190610)</font></p>

- 根据[cspiration 大佬](https://cspiration.com/leetcodeClassification)的整理 分类刷题对Leetcode题目进行了分类排序
- 根据[LiYu Lu 大佬](https://github.com/luliyucoordinate/Leetcode) 提供的答案，整理了题目答案的Jupyter

方便刷题，如侵删
- 实现过程是：
  - bat 将多个.py合并为一个(echo增加分隔符，方便阅读区分，更方便后续处理)
  - 利用excel VBA将Jupyter需要的Cell格式进行调整:
    - 对"以及\进行转义
    - 增加引号和换行符 {} [] 对
    - 可以利用echo的分隔符进行标记，然后识别标记，在对应的地方增加行
    - 增加Jupyter所需要的   "cell_type": "code", "execution_count": null, "metadata": {}, "outputs": [], "source": [
    - 特别留意转义符
    - 推荐插件 Able
    
  - 利用[JSONLint](https://jsonlint.com/)的校验，确保无误。
  - 大功告成
