# tw 编体活动
张航 && 覃狄

## 需求分析
1. 实现核心逻辑
   1. 输入输出是给定一个变化前的矩阵，然后输出变化后的矩阵
   2. 变化前的矩阵需要判断边界条件，所以抽离函数增加边界
   3. 增加边界后执行函数，需要对每一个点进行状态判断，所以抽离两个函数，一个是表示此细胞是活细胞时下一个状态，第二个是此细胞是死细胞时下一个状态。
   4. 在判断细胞下一个状态的时候，又得计算周围8个中活细胞的数量，故抽离函数计算周围活细胞的数量的函数。
   5. so on? 优化，算法优化，可以用之前写的算法多状态标志去标志原数组，然后替换，可以测试时间差，综合空间复杂度和时间复杂度定义。
   6. 运用高级数据结构以及巧妙算法（未完成）
2. 实现界面
   
3. 置顶初始状态
4. 控制动画速度

## 要求分析
1. Git 托管
   1. 小步提交，一个小功能提交一次。
2. 核心代码单元测试
   1. 核心代码的每个拆分都进行了全面的单元测试

## 自我评分分析
1. 完成度
   1. 90% 页面还是丑陋
2. 代码整洁
   1. 50% 前端不熟悉，代码很丑
3. UX
   1. 80% 细节小步提交
4. 软件工程
   1. 使用 npm 构建工具
5. 技术先进
   1. p5.js jest es6 ...


## 开发环境&工具
1. node v10.15.3
2. npm v6.9.0
3. webstorm
4. vscode
