
### 期末项目——拍照APP 

|名称|拍照APP|
|:-|:-:|
|文件现状|已完成|
|文件的主人|吴绮雯|
|设计师|吴绮雯|
|开发者|吴绮雯|
|测试者|吴绮雯|

#### 目录

- [加值宣言](#加值宣言)
- [核心价值 （最小可行性产品）](#核心价值 （最小可行性产品）)
- [背景](#背景)
- [目的](#目的)
- [目标](#目标)

- [用户](#用户)
- [用户痛点](#信息设计)
- [用户需求:（使用的人工智能要反映到需求列表中） ](#用户需求:使用的人工智能要反映到需求列表中)
- [使用者交互与设计（axure产品原型）](#使用者交互与设计)

- [产品结构图](#产品结构图)
- [API 的运用](#API 的运用 )
- [AI产品概率性](#AI产品概率性)
- [API功能对比](#API功能对比)
- [API使用风险评估](#API使用风险评估)
- [结果预期](#结果预期)
- [附录](#附录)


#### 加值宣言 
经调查，目前已有较多用于拍照的APP，例如美图秀秀、美颜相机、B612等。然而用户的需求在不断地变化，要求也日渐增多，用户对于拍照APP的要求不再仅仅只是美颜或者是拍照时加贴图，用户希望拍照念APP能够拥有更多的人性化便捷化的功能。
+ 因此，我构想的拍照APP的创新功能有：
1. 当用户站在教学楼前拍照留念时，可能会突然想起刚入学时拍下的那张照片，并且想要将那张「过去时光的照片」中的自己与现在的自己进行同框对比，但可能由于各种原因无法实现。因此我设想APP内应该有一个功能，利用人像分割功能，然后可以使用户「过去时光的照片」中的自己出现在应用中的取景器中，与眼前的场景重叠，然后合成出一张「今昔对比」的照片。
2. 可以让用户只需上传自己的一张照片，就能轻轻松松试遍所有衣服饰物
3. 可以根据用户的表情、情绪等人脸属性信息，实现特效相机、动态贴纸等互动娱乐功能
4. 拍照过程中，结合用户的手势（如点赞、比心），实时增加相应的贴纸或特效，丰富交互体验

#### 核心价值 （最小可行性产品）

着眼于用户想将现在的自己与过去的自己进行对比的需求

#### 背景
目前，对于拍照APP的这一概念，很多人认为就是为用户提供照片美化的功能软件。因此想要从市场中脱颖而出，就要另辟蹊径，满足用户更加多样化的需求。

#### 目的 
1. 让用户轻松实现「今昔对比」
2. 让用户不用亲自去到实体店，也可以知道衣服的上身效果甚至在线上就可以开始自己的时装秀
3. 让有选择困难症的用户不用再纠结拍照要选什么贴图，只需要做出一定的手势以及显露出自己的最佳表情，APP就能根据用户的表情或手势选出适合用户的贴图或特效，自动显示在取景器中


#### 目标 
+ 前期目标
实现「今昔对比」功能：用户将旧照片导入APP内，APP能够智能地将旧照片中的人像抠下来，并且抠下来的人像能够直接出现在应用中的取景器中，与眼前的场景重叠，然后生成一张对比图。

+ 中期目标
实现线上试衣的功能：用户将自己的全身照导入APP内，APP能够智能地将照片中的人像抠下来，然后用户就能开始线上试衣。

+ 后期目标
     1. 在用户拍照过程中，结合用户的手势（如点赞、比心），实时增加相应的贴纸或特效，丰富交互体验
     2. 在用户拍照时，获取用户的表情、情绪等人脸属性信息，实现特效相机、动态贴纸等互动娱乐功能

#### 用户
1. 喜欢拍照的用户
2. 想记录自身变化的用户
3. 有选择困难症的用户
4. 想在网上买衣服的用户

#### 用户痛点 
+ 场景一：用户想在同一地点，让过去的自己与现在的自己同框对比。
+ 场景二：用户在网上看到一件很漂亮的衣服，但却不知道是否适合自己，衣服的上身效果如何。
+ 场景三：想在自己的照片里增加贴图，但由于贴图的种类太多，以至于不知道该选哪一个。


#### 用户需求:（使用的人工智能要反映到需求列表中） 
|用户案例|对应标题|重要程度|
|:-|:-:|-:|
|用户想实现今昔对比|人像分割|重要|
|用户想知道衣服上身效果如何|人像分割|重要|
|用户想根据表情情绪选择合适的照片贴图或特效|人脸检测|次重要|
|用户想根据手势为图片添加贴图或特效|手势识别|次重要|

#### 使用者交互与设计（axure产品原型）

+ 拍照APP首页
![拍照APP首页](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E9%A6%96%E9%A1%B5.png)

+ 今昔对比功能
![今昔对比功能1](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BB%8A%E6%98%94%E5%AF%B9%E6%AF%941.png)
![今昔对比功能2](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BB%8A%E6%98%94%E5%AF%B9%E6%AF%942.png)

+ 线上试衣功能
![线上试衣功能1](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E7%BA%BF%E4%B8%8A%E8%AF%95%E8%A1%A31.png)
![线上试衣功能2](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E7%BA%BF%E4%B8%8A%E8%AF%95%E8%A1%A32.png)
![线上试衣功能3](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E7%BA%BF%E4%B8%8A%E8%AF%95%E8%A1%A33.png)



+ 根据用户表情自动出现贴纸或特效功能
![根据用户表情自动出现贴纸或特效功能1](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/AI%E8%A1%A8%E6%83%85%E6%8B%8D%E7%85%A71.png)
![根据用户表情自动出现贴纸或特效功能2](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/AI%E8%A1%A8%E6%83%85%E6%8B%8D%E7%85%A72.png)

+ 根据用户手势自动出现贴纸或特效功能
![根据用户手势自动出现贴纸或特效功能1](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/AI%E6%89%8B%E5%8A%BF%E6%8B%8D%E7%85%A7.png)
![根据用户手势自动出现贴纸或特效功能2](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/AI%E6%89%8B%E5%8A%BF%E6%8B%8D%E7%85%A72.png)




+ 我的
![我的1](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%88%91-%E6%B3%A8%E5%86%8C.png)
![我的2](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%88%91-%E7%99%BB%E5%BD%95.png)
![我的3](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E7%9B%B8%E5%86%8C-%E5%AE%A2%E6%9C%8D.png)


#### 产品结构图
+ 产品功能结构图
![产品功能结构图](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%8B%8D%E7%85%A7APP%E4%BA%A7%E5%93%81%E5%8A%9F%E8%83%BD%E7%BB%93%E6%9E%84%E5%9B%BE.jpg)

+ 产品信息结构图
![产品信息结构图](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%8B%8D%E7%85%A7APP%E4%BA%A7%E5%93%81%E4%BF%A1%E6%81%AF%E7%BB%93%E6%9E%84%E5%9B%BE.jpg)

+ 产品流程图
![产品流程图](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%8B%8D%E7%85%A7APP%E4%BA%A7%E5%93%81%E6%B5%81%E7%A8%8B%E5%9B%BE.jpg)

+ 产品结构图
![产品结构图](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%8B%8D%E7%85%A7APP%E4%BA%A7%E5%93%81%E7%BB%93%E6%9E%84%E5%9B%BE.jpg)

#### API 的运用 
1. 百度API——人脸检测
+ API价值主张
①检测图片中的人脸并标记出人脸坐标，支持同时识别多张人脸
②准确识别多种人脸属性信息，包括年龄、性别、种族、颜值、表情、情绪、脸型、头部姿态
③算法世界领先；服务稳定高效；灵活简单易用
④提供人脸检测与属性分析在线接口，快速检测人脸并返回人脸框位置、五官定位与轮廓关键点信息，并准确识别多种人脸属性
④基于150关键点识别，对人脸五官及轮廓自动精准定位，可自定义对人脸特定位置进行修饰美颜；同时获取表情、情绪等人脸属性信息，实现特效相机、动态贴纸等互动娱乐功能

+ 人脸检测API免费配额
![人脸检测API免费配额](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8BAPI%E5%85%8D%E8%B4%B9%E9%A2%9D%E5%BA%A6.png)

+ 人脸检测API收费标准
![人脸检测API收费标准](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8B%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86.png)

[百度API——人脸检测的详细价格](https://ai.baidu.com/docs#/BodyAnalysis-Pricing/top)

+ 请求示例：
 + HTTP方法：POST
 + 请求URL： https://aip.baidubce.com/rest/2.0/face/v3/detect


+ 请求代码示例

```
# encoding:utf-8

import requests

'''
人脸检测与属性分析
'''

request_url = "https://aip.baidubce.com/rest/2.0/face/v3/detect"

params = "{\"image\":\"027d8308a2ec665acb1bdf63e513bcb9\",\"image_type\":\"FACE_TOKEN\",\"face_field\":\"faceshape,facetype\"}"
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/json'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())

```

+ 返回结果

![返回结果](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8B%E8%BF%94%E5%9B%9E%E7%BB%93%E6%9E%9C1.png)
![返回结果](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8B%E8%BF%94%E5%9B%9E%E7%BB%93%E6%9E%9C2.png)
![返回结果](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8B%E8%BF%94%E5%9B%9E%E7%BB%93%E6%9E%9C3.png)
![返回结果](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8B%E8%BF%94%E5%9B%9E%E7%BB%93%E6%9E%9C4.png)

+ 返回示例
```
 {	
  "face_num": 1,
  "face_list": [
        {
            "face_token": "35235asfas21421fakghktyfdgh68bio",
            "location": { 
                "left": 117,
                "top": 131,
                "width": 172,
                "height": 170,
                "rotation": 4
            },
            "face_probability": 1,
            "angle" :{
                 "yaw" : -0.34859421849251
                 "pitch" 1.9135693311691  
                 "roll" :2.3033397197723  
            }
            "landmark": [  
                {
                    "x": 161.74819946289,
                    "y": 163.30244445801
                },
                ...
            ],
            "landmark72": [ 
                {
                    "x": 115.86531066895,
                    "y": 170.0546875
                }，
                ...
            ],
            "age": 29.298097610474,
            "beauty": 55.128883361816,
            "expression": {
                "type": "smile",
                "probability" : 0.5543018579483
            },
            "gender": {
                "type": "male",
                "probability": 0.99979132413864
            },
            "glasses": {
    			"type": "sun",
                "probability": 0.99999964237213
            },
            "race": {
                "type": "yellow",
                "probability": 0.99999976158142
            },
            "face_shape": {
                "type": "triangle",
                "probability": 0.5543018579483
            }
            "quality": {
                "occlusion": {
                    "left_eye": 0,
                    "right_eye": 0,
                    "nose": 0,
                    "mouth": 0,
                    "left_cheek": 0.0064102564938366,
                    "right_cheek": 0.0057411273010075,
                    "chin": 0
                },
                "blur": 1.1886881756684e-10,
                "illumination": 141,
                "completeness": 1
            }
        }
    ]
}

``` 
2. 百度API——人像分割
+ API价值主张
①将原始图片中的人像分离出来，选择新的背景图像进行替换、合成
②人像分割算法业界领先
③支持返回分割后的二值图、灰度图、人像前景图，并可通过参数设置，自主设置返回哪些结果图，避免造成带宽浪费
④对于输入的一张图片（可正常解码，且长宽比适宜），识别人体的轮廓范围，与背景进行分离，适用于拍照背景替换、照片合成、身体特效等场景。输入正常人像图片，返回分割后的二值结果图、灰度图、透明背景的人像图（png格式）。

+ 人像分割API免费配额
![人像分割API免费配额](https://raw.githubusercontent.com/DLIERBA/API_ML_AI/master/images/%E7%99%BE%E5%BA%A6API%E4%BA%BA%E5%83%8F%E5%88%86%E5%89%B2.png)

+ 人像分割API收费标准
![人像分割API收费标准](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E4%BA%BA%E5%83%8F%E5%88%86%E5%89%B2%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86.png)

[百度API——人像分割的详细价格](https://ai.baidu.com/docs#/BodyAnalysis-Pricing/top)


+ 请求示例：
 + HTTP 方法：POST
 + 请求URL： https://aip.baidubce.com/rest/2.0/image-classify/v1/body_seg

+ 请求代码示例
``` 
# encoding:utf-8

import requests
import base64

'''
人像分割
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/body_seg"
# 二进制方式打开图片文件
f = open('[本地文件]', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
``` 
+ 返回示例
```
{
	"log_id": 716033439,
	"labelmap": "xxxx",
	"scoremap": "xxxx",
	"foreground": "xxxx"
}

```


3. 百度API——手势识别
+ API价值定位：
①检测图像中的所有手部，识别手势类型，不限手势数量；支持自拍、他人拍摄、各种角度等多样化场景
②识别24种常见手势，支持单手手势和双手手势，包括拳头、OK、比心、作揖、作别、祈祷、我爱你、点赞、Diss、Rock、竖中指、数字等
③丰富的手势；领先的算法；稳定的保障

+ 手势识别API的免费配额
![手势识别API免费配额](https://raw.githubusercontent.com/DLIERBA/API_ML_AI/master/images/%E7%99%BE%E5%BA%A6API%E4%BA%BA%E5%83%8F%E5%88%86%E5%89%B2.png)

+ 手势识别API的收费标准
![手势识别API收费标准](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%89%8B%E5%8A%BF%E8%AF%86%E5%88%AB%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86.png)

[百度API——人脸检测的详细价格](https://ai.baidu.com/docs#/BodyAnalysis-Pricing/top)


+ 请求示例：
 + HTTP 方法：POST
 + 请求URL： https://aip.baidubce.com/rest/2.0/image-classify/v1/gesture

+ 请求代码示例
``` 
# encoding:utf-8

import requests
import base64

'''
手势识别
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/gesture"
# 二进制方式打开图片文件
f = open('[本地文件]', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())

``` 
+ 返回参数
![返回参数](https://raw.githubusercontent.com/DLIERBA/Fina-project/master/images/%E6%89%8B%E5%8A%BF%E8%AF%86%E5%88%AB%E8%BF%94%E5%9B%9E%E5%8F%82%E6%95%B0.png)



+ 返回示例
```
    {
        "log_id": 4466502370458351471,
    	"result_num": 2,
    	"result": [{
    		"probability": 0.9844077229499817,
    		"top": 20,
    		"height": 156,
    		"classname": "Face",
    		"width": 116,
    		"left": 173
    	},
    	{
    		"probability": 0.4679304957389832,
    		"top": 157,
    		"height": 106,
    		"classname": "Heart_2",
    		"width": 177,
    		"left": 183
    	}]
    }

```







#### AI产品概率性 
+ 百度手势识别：手势识别算法业界领先，识别准确率90%以上
+ 百度人像分割：人像分割算法业界领先，评测IoU 90%以上


#### API功能对比
1. 人脸识别API
+ 国际人脸识别评估集LFW榜， face++ 99.5% 商汤 99.53% 腾讯 99.65% 百度 99.77%，非思丸 99.77% 中科云从 99.5% 道奇智能99.64%，FaceTo 99.4% 宇泛智能 99%这些都是基于国内的
+ 百度人脸识别API，功能强大，简单易用；至少有很多人工智能的大师是在百度工作过，也是国内最早进军人工的企业之一，虽然后来大师都从百度出走，但是人家积累的根基还是很厚的。
+ face++号称是一个提供免费人脸检测、人脸识别、人脸属性分析等服务的云端服务平台，但是它所谓的免费其实就是注册和试用。但价格上应该还是可以接受的
+ 非思丸这家公司提供免费SDK，免费API，免费APK，而且不需要提供太多资料
+ 虹软技术号称提供免费的sdk，到底是怎么收费不清楚，当时对于这种不是很知名，试用就要提供一大堆个人信息还是不要用为妙。

[参考文章](https://zhuanlan.zhihu.com/p/92732557)

2. 手势识别API
+ Face++的手势识别API优势：
① 19种常见手势
② 不限手势数量
③ 适应各种光照

+ 百度的手势识别API优势：
① 检测图像中的所有手部，识别手势类型，不限手势数量；支持自拍、他人拍摄、各种角度等多样化场景
② 识别24种常见手势，支持单手手势和双手手势

+ Face++手势识别API和百度手势识别API两者的比较：
① Face++功能上的话还是比较强大的，但是没有离线版本，需要将数据进行上传，然后对JSON进行解析得到结果。
② 百度的API，基本上和Face++相同，不同之处在于返回的JSON信息以及多了一个面部信息。不过百度除了提供在线接口，还提供了离线的SDK

#### API使用风险评估
在云环境下，API提供了对应功能的访问权限，这增加了云平台的攻击面，攻击者可能存在滥用或找流行API代码中的漏洞，实现攻击云用户与云服务，因此，云安全联盟也表示不安全的API是云计算面临的最大威胁之一

+ 应对措施
1. 通过API网关进行监视
2. 安全思维贯彻开发过程始终
3. 应用行业安全最佳实践和标准

+ 参考文章：
[API安全风险](https://www.fisec.cn/854.html)
[API成为企业黑客攻击目标，你的API还安全吗？](https://baijiahao.baidu.com/s?id=1607045952862598854&wfr=spider&for=pc)

#### 产品的可行性
1. 该产品是一个APP
+ App可以实现完整功能，灵活性强
+ APP能够在交互、视觉等用户体验上满足用户的高要求
+ App的界面内容更丰富，运转速度快，系统更加流畅

2. 该产品需求明确，而且需求针对的特定的群体普遍偏年轻，其优势就是年轻群体对新鲜事物的接受度较高且具有较强的传播能力

3. 该产品有核心功能和辅助功能，功能多样而且新颖

4. 该产品能有效解决用户日常生活中较为常见的尴尬情况，

#### 交互需求 
1. 当涉及到下载或其他很耗费流量的操作时，会进行2G/3G网络还是wifi网络的判断，当判断出是非wifi时，会进行提醒。其他需要向后台请求数据时，只进行简单的网络状况是否良好的判断，当网络状况不良时进行提示。
2. 当用户上传的图片不符合要求时，会提示用户重新上传
3. 当无法识别人脸时，会提示用户重新调整好亮度和角度或者提示用户确保脸部出现在镜头内
4. 当用户摆出数据库不存在的手势，需要提示用户更换手势

#### 异常流
1. 如果人脸检测不成功，给出具体字段的错误提示信息，让用户重新调整好光亮度和角度重新拍摄
2. 如果人像分割的图像不正确，提示用户重新上传清晰的、可识别度高的图片
3. 如果用户摆出的手势是数据库内暂时不存在的，则用一种比较萌的比较人性化的语气告诉用户：亲亲，对不起吼，人家还小，还不能识别这个手势呢

#### 非功能性需求
1. 性能需求描述：
+ 响应时间：

① 在95％的情况下，一般时段响应时间不超过1.5秒，高峰时段不超过4秒。

② 定位系统从点击到第一个界面显示出来所需要的时间不得超过300毫秒。

③ 在网络畅通时，拨号连接GPRS网络所需时间不得超过5秒。

④ 在网络畅通时，电子地图刷新时间不超过10秒。

⑤ 在非高峰时间根据编号和名称特定条件进行搜索，可以在3秒内得到搜索结果。

+ 业务量：

① 估计用户数为1万人，每天登录用户数为3000左右，网络的带宽为100M带宽。

② 系统可以同时满足10,000个用户请求，并为25,000个并发用户提供浏览功能。


+ 系统容量：

① 支持3万用户，支持GB级数据。

② 数据库表行数不超过100万行，数据库最大容量不超过1000GB，磁盘空间至少需要40G以上。

+ 精度：
① 定位精度误差不超过80米。

② 当通过互联网接入系统的时候，期望在编号和名称搜索时最长查询时间<15秒。

③ 计算的精确性到小数点后7位。

+ 资源使用率：
① CPU占用率<=50%。

② 内存占用率<=50%。

2. 安全需求描述：

① 严格权限访问控制，用户在经过身份认证后，只能访问其权限范围内的数据，只能进行其权限范围内的操作。

② 不同的用户具有不同的身份和权限，需要在用户身份真实可信的前提下，提供可信的授权管理服务，保护数据不被非法/越权访问和篡改，要确保数据的机密性和完整性。

③ 提供运行日志管理及安全审计功能，可追踪系统的历史使用情况。

④ 能经受来自互联网的一般性恶意攻击。如病毒（包括木马）攻击、口令猜测攻击、黑客入侵等。

⑤ 至少99%的攻击需要在10秒内检测到。

⑥ 当用户的账号在常用设备以外的设备登录了，要及时发消息通知用户；当用户出现登录异常的情况时，要开启动态口令验证（例如短信发生动态码）等。

3. 可靠性需求描述：

① 对输入有提示，数据有检查，防止数据异常。

② 系统健壮性强，应该能处理系统运行过程中出现的各种异常情况，如：人为操作错误、输入非法数据、硬件设备失败等，系统应该能正确的处理，恰当的回避。

③ 因软件系统的失效而造成不能完成业务的概率要小于5‰。

④ 要求系统7x24小时运行，全年持续运行故障停运时间累计不能超过10小时。

⑥ 系统缺陷率每1,000小时最多发生1次故障。

⑥ 在1,000,000次交易中，最多出现1次需要重新启动系统的情况。

4. 兼容性需求描述：

① 系统应支持IOS，Android 操作系统

② 系统应支持Oracle, DB2 数据库系统

③ 替换关系数据库系统的平均时间不超过2小时，并且保证没有数据丢失。

5. 数据保密需求描述：

网络传递数据应经过加密。需要保证数据在采集、传输和处理过程中不被偷窥、窃取、篡改。业务数据需要在存储时进行加密，确保不可破解。



6. 易用性需求描述案例：
 功能操作简单，界面清晰简洁，某些较复杂的操作需要给用户提供操作指引。

7. 可用性需求描述：

① 有些农村地区网络质量差，带宽小。在网络环境差的条件下保证系统的可用性等。

② 在95%的故障中，系统最多需要20秒重启。

③ 提供数据备份和恢复功能，使得在由于系统的错误或其他原因引起系统的数据丢失或系统的数据被破坏时，能够及时恢复和还原数据（由硬件及第三方软件提供此功能）。

8. 可测试性需求描述：

① 一个模块的最大圈复杂度不能超过15。

② 开发活动必须使用回归测试，并允许在12小时内重新进行完整的测试。

9. 可维护性需求描述：

① 从接到修改请求后，对于普通修改应在1~2天内完成；对于评估后为重大需求或设计修改应在1周内完成。

② 90%的BUG修改时间不超过1个工作日，其他不超过2个工作日。

③ 代码的圈复杂度必须在10以内。

④ 任何对象的任何方法都不允许超过200行代码。

⑤ 安装新版本必须保持所有的数据库内容和所有个人设置不变。

⑥ 产品必须提供可跟踪任何数据库字段的工具。

[参考文章](https://blog.csdn.net/zhangjunli/article/details/102968598)

#### 结果预期
+ 上线初期，先在一个小区域内（例如某个地区的高校）进行推广，然后收集这一部分使用者的体验评价，根据情况进行完善
+ 当APP功能基本完善，用户评价普遍向好时，面向整个市场推出使用，不过刚开始需要使用一些奖励措施，吸引更多的用户使用APP
+ 到APP被广泛应用，拥有较为稳定的用户群体时，可减少甚至取消先前为了吸引新用户所采取的奖励，并且可以考虑增加其他功能，利用持续创新的手段吸引新用户以及留住旧用户
+ 发展到一定阶段后，APP可能会接手广告业务获利；或者在APP内开设购物功能，贩卖周边之类的；也有可能选择增设会员服务，以吸引用户在APP内消费，最终实现APP盈利
#### 附录
[拍照APP原型完整版]( http://nfunm080.gitee.io/photo_app)
