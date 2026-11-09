# Shan Hai Jing Bestiary: creatures of the Classic of Mountains and Seas

An open dataset of 43 creatures from the *Shan Hai Jing* (山海经, Classic of Mountains and Seas), the ancient Chinese book of geography and myth. Each record has the creature's name in Chinese and pinyin, where it appears in the book, the original Chinese text and an English translation.

The full illustrated bestiary, with the legends behind each creature, lives at **[morrowblue.com/shan-hai-jing](https://morrowblue.com/shan-hai-jing/)**. This repository is the plain data behind it.

## Files

- `data/beasts.json`: one object per creature.
- `data/beasts.csv`: the same data as a spreadsheet (UTF-8).

Fields: `slug`, `name`, `chinese`, `pinyin`, `in_shan_hai_jing`, `source_book`, `source_place`, `original_text`, `translation`, `url`.

## Example

```json
{
  "slug": "nine-tailed-fox",
  "name": "Nine-Tailed Fox",
  "chinese": "九尾狐",
  "pinyin": "jiǔwěihú",
  "in_shan_hai_jing": true,
  "source_book": "Southern Mountains, Book 1",
  "source_place": "Mount Qingqiu",
  "original_text": "有兽焉，其状如狐而九尾，其音如婴儿，能食人，食者不蛊。",
  "translation": "A beast lives here, like a fox with nine tails and a cry like a baby's. It eats people. Whoever eats it is safe from curses.",
  "url": "https://morrowblue.com/shan-hai-jing/nine-tailed-fox/"
}
```

## Creatures

| Name | Chinese | Pinyin | Where in the book |
|---|---|---|---|
| [Bai Ze](https://morrowblue.com/shan-hai-jing/bai-ze/) | 白泽 | báizé | Yunji Qiqian: Annals of the Yellow Emperor, Mount Huan |
| [Bashe](https://morrowblue.com/shan-hai-jing/bashe/) | 巴蛇 | bāshé | Within the Seas: South, Land of Ba |
| [Bifang](https://morrowblue.com/shan-hai-jing/bifang/) | 毕方 | bìfāng | Western Mountains, Book 3, Mount Zhang'e |
| [Biyi Bird](https://morrowblue.com/shan-hai-jing/biyiniao/) | 比翼鸟 | bǐyìniǎo | Beyond the Seas: South, East of the Southern Mountain |
| [Bo](https://morrowblue.com/shan-hai-jing/bo/) | 駮 | bó | Western Mountains, Book 4, Mount Zhongqu |
| [Boyi](https://morrowblue.com/shan-hai-jing/boyi/) | 猼訑 | bóyí | Southern Mountains, Book 1, Mount Ji |
| [Chenghuang](https://morrowblue.com/shan-hai-jing/chenghuang/) | 乘黄 | chénghuáng | Beyond the Seas: West, Land of the Baimin |
| [Chiru](https://morrowblue.com/shan-hai-jing/chiru/) | 赤鱬 | chìrú | Southern Mountains, Book 1, Ying River, Mount Qingqiu |
| [Dangkang](https://morrowblue.com/shan-hai-jing/dangkang/) | 当康 | dāngkāng | Eastern Mountains, Book 4, Mount Qin |
| [Fei](https://morrowblue.com/shan-hai-jing/fei/) | 蜚 | fěi | Eastern Mountains, Book 4, Mount Tai |
| [Feiyi](https://morrowblue.com/shan-hai-jing/feiyi/) | 肥遗 | féiyí | Western Mountains, Book 1, Mount Taihua |
| [Fenghuang](https://morrowblue.com/shan-hai-jing/fenghuang/) | 凤皇 | fènghuáng | Southern Mountains, Book 3, Mount Danxue |
| [Gudiao](https://morrowblue.com/shan-hai-jing/gudiao/) | 蛊雕 | gǔdiāo | Southern Mountains, Book 2, Mount Luwu |
| [Heluoyu](https://morrowblue.com/shan-hai-jing/heluoyu/) | 何罗鱼 | héluóyú | Northern Mountains, Book 1, Qiao River, Mount Qiaoming |
| [Huashe](https://morrowblue.com/shan-hai-jing/huashe/) | 化蛇 | huàshé | Central Mountains, Book 2, Mount Yang |
| [Hundun](https://morrowblue.com/shan-hai-jing/hundun/) | 混沌 | hùndùn | Western Mountains, Book 3, Mount Tian |
| [Jiaochong](https://morrowblue.com/shan-hai-jing/jiaochong/) | 骄虫 | jiāochóng | Central Mountains, Book 6, Mount Pingfeng |
| [Jingwei](https://morrowblue.com/shan-hai-jing/jingwei/) | 精卫 | jīngwèi | Northern Mountains, Book 3, Mount Fajiu |
| [Jufu](https://morrowblue.com/shan-hai-jing/jufu/) | 举父 | jǔfù | Western Mountains, Book 3, Mount Chongwu |
| [Kui](https://morrowblue.com/shan-hai-jing/kuiniu/) | 夔 | kuí | Great Wilderness: East, Mount Liubo |
| [Lili](https://morrowblue.com/shan-hai-jing/lili/) | 狸力 | lílì | Southern Mountains, Book 2, Mount Gui |
| [Lu Wu](https://morrowblue.com/shan-hai-jing/luwu/) | 陆吾 | lùwú | Western Mountains, Book 3, Kunlun Hill |
| [Luoyu](https://morrowblue.com/shan-hai-jing/luoyu/) | 蠃鱼 | luǒyú | Western Mountains, Book 4, Meng River, Mount Gui |
| [Lushu](https://morrowblue.com/shan-hai-jing/lushu/) | 鹿蜀 | lùshǔ | Southern Mountains, Book 1, Mount Niuyang |
| [Mafu](https://morrowblue.com/shan-hai-jing/mafu/) | 马腹 | mǎfù | Central Mountains, Book 2, Mount Manqu |
| [Mengji](https://morrowblue.com/shan-hai-jing/mengji/) | 孟极 | mèngjí | Northern Mountains, Book 1, Mount Shizhe |
| [Nine-Tailed Fox](https://morrowblue.com/shan-hai-jing/nine-tailed-fox/) | 九尾狐 | jiǔwěihú | Southern Mountains, Book 1, Mount Qingqiu |
| [Qinggeng](https://morrowblue.com/shan-hai-jing/qinggeng/) | 青耕 | qīnggēng | Central Mountains, Book 11, Mount Jinli |
| [Qinyuan](https://morrowblue.com/shan-hai-jing/qinyuan/) | 钦原 | qīnyuán | Western Mountains, Book 3, Kunlun Hill |
| [Qiongqi](https://morrowblue.com/shan-hai-jing/qiongqi/) | 穷奇 | qióngqí | Western Mountains, Book 4, Mount Gui |
| [Taotie](https://morrowblue.com/shan-hai-jing/taotie/) | 饕餮 | tāotiè | Northern Mountains, Book 2, Mount Gouwu |
| [Tiangou](https://morrowblue.com/shan-hai-jing/tiangou/) | 天狗 | tiāngǒu | Western Mountains, Book 3, Mount Yin |
| [Tianwu](https://morrowblue.com/shan-hai-jing/tianwu/) | 天吴 | tiānwú | Beyond the Seas: East, Zhaoyang Valley |
| [Tulou](https://morrowblue.com/shan-hai-jing/tulou/) | 土蝼 | tǔlóu | Western Mountains, Book 3, Kunlun Hill |
| [Xingxing](https://morrowblue.com/shan-hai-jing/xingxing/) | 狌狌 | xīngxīng | Southern Mountains, Book 1, Mount Zhaoyao |
| [Xiqu](https://morrowblue.com/shan-hai-jing/xiqu/) | 犀渠 | xīqú | Central Mountains, Book 4, Mount Li |
| [Xuangui](https://morrowblue.com/shan-hai-jing/xuangui/) | 旋龟 | xuánguī | Southern Mountains, Book 1, Guai River, Mount Niuyang |
| [Yinglong](https://morrowblue.com/shan-hai-jing/yinglong/) | 应龙 | yìnglóng | Great Wilderness: East, Xiongli Earth Hill |
| [Yufu](https://morrowblue.com/shan-hai-jing/yufu/) | 鱼妇 | yúfù | Great Wilderness: West, Land of the Huren |
| [Zheng](https://morrowblue.com/shan-hai-jing/zheng/) | 狰 | zhēng | Western Mountains, Book 3, Mount Zhang'e |
| [Zhulong](https://morrowblue.com/shan-hai-jing/zhulong/) | 烛龙 | zhúlóng | Great Wilderness: North, Mount Zhangwei |
| [Zhuru](https://morrowblue.com/shan-hai-jing/zhuru/) | 朱獳 | zhūrú | Eastern Mountains, Book 2, Mount Geng |
| [Zhuyan](https://morrowblue.com/shan-hai-jing/zhuyan/) | 朱厌 | zhūyàn | Western Mountains, Book 2, Mount Xiaoci |

## Notes on the text

- The Chinese text follows common modern editions in simplified characters. Where Guo Pu's 4th-century commentary matters, it is included in brackets.
- Translations are our own and stay close to the original wording.
- Bai Ze is not in the Shan Hai Jing. It is included because readers often assume it is; its record cites the later Daoist text where it does appear.
- Corrections are welcome. Please open an issue with the edition and passage.

## License

The original Chinese text is in the public domain. The English translations and the dataset are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). If you reuse them, please credit **Morrow Blue** with a link to https://morrowblue.com/shan-hai-jing/.

## About

Made by [Morrow Blue](https://morrowblue.com/), an independent studio making games and guides about Chinese mythology. The creatures here are also the units of [Beasts of Shanhai](https://morrowblue.com/beasts-of-shanhai/), a free browser auto battler. For gods, dragons and other figures beyond this book, see the [Chinese mythology encyclopedia](https://morrowblue.com/chinese-mythology/).
