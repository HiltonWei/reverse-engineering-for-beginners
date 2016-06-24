# Reverse engineering for beginners

## 说明

该项目为某同性交友团体翻译某本bl文的项目地址，异性恋请勿[点击](index.md)

## 源起

两年前乌云知识库的 @瞌睡龙 菊苣发起对《Reverse engineering for beginners》本书的翻译项目，但是后期对这本书都没怎么做过修缮工作，以至于两年间Dennis Yurichev对这本书的调整修改都得不到更新。而且乌云译版里面还有着不少语句不通，格式混乱的瑕疵。作为之前参加过这项翻译工作实在不忍心看着这么好的逆向书在中国的技术社区上被埋没。

恰巧在前几天在Dennis Yurichev菊苣的[主页](http://beginners.re/)上看到《reverse engineering for beginners》的韩语版已经出版发售。而相比之下这本书在中国的技术社区上却显得很冷清，我尝试搜了一下，目前还没找到乌云译版以外的翻译版本。中文翻译版可以在Dennis Yurichev的blog看找到链接http://yurichev.com/blog/2015-aug-20/。不过Dennis Yurichev的感谢列表说antiy也有一份Chinese的翻译版本，但是我没找到，如果有小伙伴知道的麻烦告诉我一声，谢谢: )

![](http://static.wooyun.org/upload/image/201605/2016052513120168158.png)

我目前看过的逆向书籍不多，但是对比一下国内看雪社区的《加密与解密》，《reverse engineering for beginners》还是更适合作为逆向入门书籍，而且里面覆盖的范围更广，包括了x86/x64，arm两三种CPU的指令集，而且囊括了Linux和Windows的OS hack等内容，各种逆向工具也都介绍了一番。所以逆向方面我挺推荐这本书作为入门读物的。

## 修缮计划

1. 对每个章节都review并修缮，把语病，格式混乱等问题给解决了。
2. 里面大量的术语翻译不一致，格式不一致，这方面也要做改善。
3. 因为这期间作者对原版调整了很多，有不少章节缺漏或被删，分章情况也大不相同，所以需要继续完善跟原版的衔接工作。
4. 迁移到gitbook和看云上，并在乌云drops上开一个专题连载这本书，提供一个更好的阅读体验。
5. 因为乌云主分支的管理员比较少上线，所以先在我的github分支上做修缮工作，之后任务差不多了再归并到主分支上。

## 任务分配计划

- 统一化翻译术语和格式。
- 目录调整，将每章章节都和原版进行归并。
- 补全和删除掉与原版不符合的章节，之前翻译的时候是800多页，现在已经1300多页。
- 文章校验工作，最好每章都有人可以帮忙维护校对。
- gitbook上电子书的建设和维护。
- 看云上电子书的建设和维护。
- 乌云drops上电子书的建设和维护。

## 贡献名单

### 第一期的翻译贡献人员

瞌睡龙、糖果、blast、magix526、Larryxi、左懒、DM_、Zing

### 修缮工作的贡献人员

如有缺漏请通知我一声。谢谢！

## Copyright

原书版权归Dennis Yurichev作者所有，翻译解释权归所有参加过翻译的乌云社区小伙伴所有。

## 最后

最后，我在乌云zone上面发布了一个悬赏贴，里面就悬赏给第一个contributor了：）

http://zone.wooyun.org/content/27463

希望有兴趣的同学一起帮忙完善这本书吧！

- 原版：https://github.com/dennis714/RE-for-beginners
- 乌云主分支：https://github.com/woolabs/Reverseng
- 我的github上面的分支：https://github.com/veficos/reverse-engineering-for-beginners
