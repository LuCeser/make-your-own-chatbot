# Make Your Own Chatbot

## 1. 前言

计算机行业的祖师爷之一图灵在他1950年的一篇关于机器智能的论文中提出了一个关于如何测试机器是否拥有智能的思维实验，既大名鼎鼎的图灵测试。图灵测试可以简述为，将一个人与一台计算机隐藏在幕后，我们通过与其对话，如果不能分辨幕后的哪一个是人类哪一个是计算机，那我们就可以认为这台计算机拥有了人类的智能。

我认为这个思维实验的另一个有意思的地方在于，我们通过对话的方式去判断一台计算机、一个程序是否拥有智能是很符合我们一贯直觉的。

人类自己通过对话的方式交流思想，表达自己的想法，因此我们也希望通过这种方式来与计算机进行交流。这也是符合大众心目中对于人工智能的直观感受的：对话，交流，思想。

当然我的目标没有那么宏大，现今机器学习的发展势头很猛，深度学习的应用更是将图像识别，语音识别这些原本机器并不擅长领域提升到与人类相同的水平。但是NLP（自然语言处理，Natural Language Process）没有像图像识别，语音识别那样出现翻天覆地的变化，我们还是无法创造出一个有思维的机器人，当然这也不是这个项目的目标。

## 2. NLP的难题

自然语言的一大特点就是语言的复杂性程度太高了，歧义性也很难消除，就算是人类在相互交流的时候，如果互相没有相同的背景，交流起一些话题的时候也会出现鸡同鸭讲的情况。因此纯粹的基于概率的统计是很难达到满意的效果。同一个词语在不同语境下的含义会千差万别，这就是不同领域之间的差别了。同一个词，如果去计算出现的概率的话，使用不同的语料库进行训练得到的结果可能大相径庭。按照统计来说，我们对于可能出现的下一个词有着相关概率的统计，而这个统计的依据就是我们训练所使用的语料。 

综上所述，我们很难做出一个全知全能的聊天机器人，在现有的技术条件下我们可以做出一个在专业领域很强的聊天机器人，这也是这个项目的最终目标。

## 3. 项目的目标

这个项目是一个学习过程，并不是一个教程，所以不可避免的会有许多错误，也必然有许多可笑的想法，我的目标是在这个项目中逐渐摸索出一个可以对话的聊天机器人。

