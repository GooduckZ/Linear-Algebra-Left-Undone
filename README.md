# 线性代数：未竟之美

## 为什么会有这个仓库
线性代数作为很多同学大学接触的第一门数学课，一方面其重要性不言而喻，在很多专业中都是必要的预修知识，另一方面其内容也是很多同学第一次接触如此抽象的数学内容，因此在学习线性代数时会遇到很多困难.

特别是浙江大学图灵班同学两学期要面对的《大学数学：代数与几何》（第二版）和《线性代数应该这样学》（第三版）两本教材，第一本直接从抽象的线性空间和线性映射引入，抛弃了传统工科线性代数从行列式起步的教授方式，更能让同学了解线性代数的本质，但入门存在一些困难. 而第二本教材风格则更偏向于数学专业课，全篇不谈矩阵计算，以“算子”为核心，最后引入行列式，其目的只是为了表明他所讲的内容和传统线性代数是统一的，但却更加深入.

我想如果能将这两本教材学好，线性代数的基础将会是非常扎实. 但理念与实际执行有很大的偏差，并非所有同学都能在初学时完全接受抽象的教学方式. 除此之外，线性代数（或高等代数）还有很多的参考资料（如丘维声老师的高等代数，或是 Strang 老先生的线性代数，或是 3b1b 的线性代数的几何本质），但同学们如果完全投入时间到这些参考书，很容易陷入迷茫，并且与最终的考试风格也相距较远. 一次我们希望有一本讲义能综合这些资料中与这两门课的学习关联的部分，优化内容安排，并安排足量的习题供同学练习，以便同学们能够更好地学习线性代数.

## 我们的讲义包含了什么
我们的讲义针对浙江大学图灵班线性代数Ⅰ和Ⅱ的两本教材，希望搭建一个较为完整的线性代数学习体系.

基于我们之前所说的目的，我们希望这份讲义是兼容多本教材的特色的. 一方面我们希望能从更专业的视角，而非一般的工科线性代数的角度讲述线性代数，又能更加贴合同学对通过考试的需求，找寻更好的切入点介绍知识，并配套大量习题（并提供参考答案）供同学练习，其中不乏往年考试真题. 总之，我们希望这份讲义是对教材的补充，是融合了很多资料的观点的深入浅出的一份参考.

除此之外，我们的讲义还会包含一些微专题，附在部分章节之后，其主要目的是介绍一些线性代数概念的几何意义，介绍一些线性代数的应用，也会有一些延伸和拓展的内容.

当然这份讲义中有大量的内容是与我们的参考教材紧密联系的，因此推荐阅读本讲义时结合教材进行阅读.

## 贡献手册

如果你希望为这个项目做出贡献，你需要了解或遵循的是：
- 本项目的许可证为 [![CC BY-NC-SA Logo](https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png) 知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)
- 本仓库目前有两个分支，当前 `new` 为主分支，也是贡献的提交分支，`main` 为 2022-2023 学年秋冬学期的版本，在编写部分章节时可以直接截取其中的内容
- 贡献方式
    - Pull Request（推荐）：推荐通过 PR（即 Pull Request）的形式来进行贡献，具体流程：
        - 在 GitHub 网页端点击右上角的 fork，将本仓库 fork 到自己的帐号下
        - 在自己帐号的对应仓库中进行修改
        - 修改完成后，点击 New Pull Request，提交一个 PR
        - 等待其他人审核、修改，然后合并到本 repo 中
    - 如果要修改的内容不多，只是一些 typo 等，或是有更好的编写思路等可以通过提 issue 的方式与我们进行交流
    - 鼓励贡献者使用 `latexindent` 格式化文档. 您的 Pull Request 将在格式化之后 squash 合并至本仓库
    - 特别注意：如果你不是本项目的合作者，请不要直接向本仓库 push，这样的行为都将是无效的
- 讲义部分请严格按照当前文件结构进行提交，即保持现有的章节目录，图片放在 `figs` 文件夹中. 如果有文件结构上的改变请先提 issue 或直接与我通过邮件/QQ 等方式交流

## 手动编译

在仓库目录下运行 `make` 编译讲义与习题参考答案，运行 `make main` 或 `make ans` 分别编译，或在对应文件夹下运行 `make`. 编译完成的 PDF 位于对应文件夹下.
