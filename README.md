#实验报告

##实验目的

#####掌握字符串String及其方法的使用

#####掌握异常处理结构

##核心代码
```javascript
String str2 = "";
		for (int i = 0; i < str.length(); i++) {
			if (i * 7 + 7 > str.length()) {
				str2 += str.substring(i * 7, str.length());
				break;
			}}
```
```javascript
public static int count(StringBuilder str, String findStr) {
		int count = 0;
		int index = 0;
		while ((index = str.indexOf(findStr, index)) != -1) {
			index = index + findStr.length();
			count++;
}}
```
##实验结果
`汉皇重色思倾国,御宇多年求不得.`
`杨家有女初长成,养在深闺人未识.`
`天生丽质难自弃,一朝选在君王侧.`
`回眸一笑百媚生,六宫粉黛无颜色.`
`春寒赐浴华清池,温泉水滑洗凝脂.`
`侍儿扶起娇无力,始是新承恩泽时.`
`云鬓花颜金步摇,芙蓉帐暖度春宵.`
`春宵苦短日高起,从此君王不早朝.`
`承欢侍宴无闲暇,春从春游夜专夜.`
`后宫佳丽三千人,三千宠爱在一身.`
`金屋妆成娇侍夜,玉楼宴罢醉和春.`
`姊妹弟兄皆列土,可怜光彩生门户.`
`天出现的次数为:1`
##实验感想
使我更加的理解和熟练的运用字符串及循环操作。
