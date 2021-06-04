1.您的年级是 [单选题]
2007级
2006级
2005级
2004级

2.您的年级是 [多选题]
2007级
2006级
2005级
2004级

3.请对学校的安全管理制度的满意度作个评价 [量表题]
很不满意
不满意
一般
满意
很满意

4.请对学校的安全管理制度的满意度作个评价 [矩阵单选]
很不满意 不满意 一般 满意 很满意
寝室里面用电安全管理
食堂就餐安全管理

5.请对学校的安全管理制度的满意度作个评价 [矩阵多选]
很不满意 不满意 一般 满意 很满意
寝室里面用电安全管理
食堂就餐安全管理

6.您有哪些意见？[单项填空]


http://172.16.185.134/survey/#/batchcreate?id=73c3b1b55b92496e863e541ca79588b1


富文本插件 - CKEDITOR
1、word粘贴的格式要保留
2、粘贴进的图片要保留
3、题目的解析，涉及到html标签，以及公式，公式的格式一般为

\[f(x) = {{{a_0}} \over 2} + \sum\limits_{n = 1}^\infty {({a_n}\cos {nx} + {b_n}\sin {nx})}\]
$$f(x) = {{{a_0}} \over 2} + \sum\limits_{n = 1}^\infty {({a_n}\cos {nx} + {b_n}\sin {nx})}$$
$$f(x) = {{{a_0}} \over 2} + \sum\limits_{n = 1}^\infty {({a_n}\cos {nx} + {b_n}\sin {nx})}$$
$f(x) = {{{a_0}} \over 2} + \sum\limits_{n = 1}^\infty {({a_n}\cos {nx} + {b_n}\sin {nx})}$


每周四中午我们碰一下目前的问题点

ckeditor关于wps的issue   https://github.com/ckeditor/ckeditor5/issues/2488

let regexPictureHeader = /{\\pict[\s\S]+?\\bliptag-?\d+(\\blipupi-?\d+)?({\\\*\\blipuid\s?[\da-fA-F]+)?[\s}]*?/;
let regexPicture = new RegExp( '(?:(' + regexPictureHeader.source + '))([\\da-fA-F\\s]+)\\}', 'g' );
let images = rtfData.match( regexPicture );
let result = [];

if ( !images ) {
  console.log(images, '走了新规则')
  regexPictureHeader = /{\\pict[\s\S]+?(\\pngblip-?\d+)?(\\wmetafile8-?\d+)?{\\\*\\blipuid\s?[\da-fA-F]+[\s}]*?/;
  regexPicture = new RegExp( '(?:(' + regexPictureHeader.source + '))([\\da-fA-F\\s]+)\\}', 'g' );
  images = rtfData.match( regexPicture );
}
