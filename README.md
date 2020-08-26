# GoogleTranslateMakeGrass
谷歌翻译生草机

首先，请先使用pip安装相应的库：

```bash
pip install googletrans
```

然后请下载项目，并将mg.py放在您的工程项目的同一目录下。

在您的项目中导入：

```python
import mg
```

并且使用方法:

```python
mg.makeGrass(text,times)
```

其中，text位str类型，是要翻译的内容；

times是可选参数，为翻译次数，默认为10；

-------------------------
demo：

谷歌翻译生草机：
原文：
晋太元中，武陵人捕鱼为业。缘溪行，忘路之远近。忽逢桃花林，夹岸数百步，中无杂树，芳草鲜美，落英缤纷，渔人甚异之，复前行，欲穷其林。

林尽水源，便得一山，山有小口，仿佛若有光。便舍船，从口入。初极狭，才通人。复行数十步，豁然开朗。土地平旷，屋舍俨然，有良田美池桑竹之属。阡陌交通，鸡犬相闻。其中往来种作，男女衣着，悉如外人。黄发垂髫，并怡然自乐。

见渔人，乃大惊，问所从来。具答之。便要还家，设酒杀鸡作食。村中闻有此人，咸来问讯。自云先世避秦时乱，率妻子邑人来此绝境，不复出焉，遂与外人间隔。问今是何世，乃不知有汉，无论魏晋。此人一一为具言所闻，皆叹惋。余人各复延至其家，皆出酒食。停数日，辞去。此中人语云：“不足为外人道也。”

既出，得其船，便扶向路，处处志之。及郡下，诣太守，说如此。太守即遣人随其往，寻向所志，遂迷，不复得路。

南阳刘子骥，高尚士也，闻之，欣然规往。未果，寻病终，后遂无问津者。

--------------------------------------------------------------------
翻译后：

金朝时期在太原，武陵人捕鱼。在河边旅行，忘记了路的距离。突然之间，有一个桃花林，距另一边几百步之遥，中间没有杂树，香草可口，落花缤纷。渔民有很大的不同。

当森林到达水源时，山上有一小口，好像有光。方便船从口进入。刚开始时，人才非常狭窄。经过几十个步骤，它突然变得清晰起来。土地平坦，房屋像桑树和竹子。在稻田里，鸡狗的交通互相听见。其中，男人和女人打扮得像局外人。当黄色的头发掉下来时，他感到非常高兴。

看到渔夫，我很震惊，问了所有人。顾回答。他们不得不返回家乡并建立酒精来杀死鸡肉作为食物。当村里听说这样的人时，他来问问题。因为Yun贤石避免了秦朝的混乱，使他的妻子和其他人陷入了这种绝望的局面，没有回到祖国，所以他在外界的控制下被孤立了。问今天的生活，我不知道是否有汉族。这与魏晋时代无关。这个人非常敬业，每个人听到时都叹了口气。其余的人回家喝酒和吃饭。停几天，然后辞职。有人说：“局外人还不够。”

一旦下车乘船，您将帮助您上路并瞄准任何地方。县长是这样说的。县治长派人跟随他，寻找他想要的东西，迷路了，不再找到路。

一位贵族学者南洋刘子集得知此事后高兴地离开了。失败了，最终病了，没人感兴趣。
