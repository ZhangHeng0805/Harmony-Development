# Harmony-Development
# Harmony开发笔记

## 一、准备工作

官方网址：https://www.harmonyos.com/

<!-- ### 1、完整开发流程
![1631257995126](https://user-images.githubusercontent.com/74289276/138595268-8a901c00-7c15-477e-a19c-40e120661336.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595268-8a901c00-7c15-477e-a19c-40e120661336.png" alt="1631257995126" style="zoom:25%;" />

### 2、开发工具下载和安装

####  [开发工具下载](https://developer.harmonyos.com/cn/develop/deveco-studio#download )

#### 开发工具安装：
![QQ截图20210910152207](https://user-images.githubusercontent.com/74289276/138595357-80f361ef-3971-410f-9d14-1bae64ee37bc.png)
![QQ截图20210910152831](https://user-images.githubusercontent.com/74289276/138595399-72fa5038-08fd-4b26-9236-71a9ab7643df.png)

然后依次点击 ***Next***  >>>***Install***，等待进度条读满，最后点击***Finish***即可完成安装

安装完成后，在桌面点击快捷启动图标打开开发工具
![QQ截图20210910154034](https://user-images.githubusercontent.com/74289276/138595428-e3590fa3-cb95-4d61-907b-6d63c88c9b66.png)
<!-- ![](\笔记图片\QQ截图20210910154034.png) -->

<!-- ![QQ截图20210910154222](https://user-images.githubusercontent.com/74289276/138595445-4f48b445-07c3-4423-96e8-75dfaf72d96e.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595445-4f48b445-07c3-4423-96e8-75dfaf72d96e.png" style="zoom:80%;" />

<!-- ![1631259855753](https://user-images.githubusercontent.com/74289276/138595467-1e8fc321-60d9-461b-9342-5d28ec393023.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595467-1e8fc321-60d9-461b-9342-5d28ec393023.png" style="zoom: 67%;" />

<!-- ![QQ截图20210910154806](https://user-images.githubusercontent.com/74289276/138595517-e9d26c14-3b90-4764-b26e-d2e8f05dbc28.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595517-e9d26c14-3b90-4764-b26e-d2e8f05dbc28.png" style="zoom: 67%;" />

<!-- ![QQ截图20210910155325](https://user-images.githubusercontent.com/74289276/138595574-d8548b84-b043-4778-ae40-e124c10c74a6.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595574-d8548b84-b043-4778-ae40-e124c10c74a6.png" style="zoom:67%;" />

<!-- ![QQ截图20210910155513](https://user-images.githubusercontent.com/74289276/138595595-2603ea8e-e1a5-4b3d-a1f5-072e8914e03f.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595595-2603ea8e-e1a5-4b3d-a1f5-072e8914e03f.png" style="zoom:67%;" />

<!-- ![QQ截图20210910155715](https://user-images.githubusercontent.com/74289276/138595616-844985d7-e52d-4b7d-8d1a-4a8b5edceadf.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595616-844985d7-e52d-4b7d-8d1a-4a8b5edceadf.png" style="zoom:67%;" />

<!-- ![QQ截图20210910155907](https://user-images.githubusercontent.com/74289276/138595632-3d565dd5-d087-4622-8e0f-6d009021959e.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595632-3d565dd5-d087-4622-8e0f-6d009021959e.png" style="zoom:57%;" />

检查SDK安装情况
<!-- ![QQ截图20210910160254](https://user-images.githubusercontent.com/74289276/138595652-c5a31890-7fd5-4a83-ac42-948c74e2fc23.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595652-c5a31890-7fd5-4a83-ac42-948c74e2fc23.png" style="zoom:67%;" />

到此开发工具的安装已经完成

### 3、项目结构
<!-- ![QQ截图20210910160811](https://user-images.githubusercontent.com/74289276/138595676-74a246f1-56ea-4b0b-98a8-e7b2dd73ab1c.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595676-74a246f1-56ea-4b0b-98a8-e7b2dd73ab1c.png" style="zoom:50%;" />

目录结构
<!-- ![QQ截图20210910161212](https://user-images.githubusercontent.com/74289276/138595707-7953cce6-c4f0-402d-8e8e-6bafd952c2e6.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595707-7953cce6-c4f0-402d-8e8e-6bafd952c2e6.png" style="zoom: 67%;" />

### 4、鸿蒙入门应用

#### 第一个入门应用：HelloWorld

新建项目之后，自带HelloWord,在第一个案例中需要注意以下几点：

##### 如何运行项目

- 登录账号
<!-- ![QQ截图20210910162106](https://user-images.githubusercontent.com/74289276/138595730-fa86dcfe-15b3-4c1e-b5ad-47b4ee43a623.png) -->
  <img src="https://user-images.githubusercontent.com/74289276/138595730-fa86dcfe-15b3-4c1e-b5ad-47b4ee43a623.png" style="zoom: 40%;" />

- 选择并开启模拟器
<!-- ![QQ截图20210910162253](https://user-images.githubusercontent.com/74289276/138595747-dfae7551-426a-49e2-8556-a26d6eb8e8bf.png) -->
  <img src="https://user-images.githubusercontent.com/74289276/138595747-dfae7551-426a-49e2-8556-a26d6eb8e8bf.png" style="zoom:50%;" />

- 运行项目
<!-- ![QQ截图20210910162421](https://user-images.githubusercontent.com/74289276/138595761-8fb5016d-4a3d-4011-88df-cadb830b9db8.png) -->
  <img src="https://user-images.githubusercontent.com/74289276/138595761-8fb5016d-4a3d-4011-88df-cadb830b9db8.png" style="zoom:50%;" />

##### 页面中的包含关系
<!-- ![QQ截图20210910162758](https://user-images.githubusercontent.com/74289276/138595781-c56f7ccf-f3ef-49c6-9ee3-b32ce8beec9a.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595781-c56f7ccf-f3ef-49c6-9ee3-b32ce8beec9a.png" style="zoom:50%;" />

- 一个App里面包含多个Hap包，每个Hap包都对应一个App的功能，可以单独下载，类似于微服务
<!-- ![QQ截图20210910162927](https://user-images.githubusercontent.com/74289276/138595806-00288f8a-1271-4d59-b87c-9bb0afca14f8.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595806-00288f8a-1271-4d59-b87c-9bb0afca14f8.png" style="zoom:50%;" />

<!-- ![QQ截图20210910163218](https://user-images.githubusercontent.com/74289276/138595826-e9aca9f8-6054-4fc0-95fd-cbf3a4c09113.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595826-e9aca9f8-6054-4fc0-95fd-cbf3a4c09113.png" style="zoom:50%;" />

**包含关系:**
	最外面是: Ability
	Ability中是-个或多个子页面: AbilitySlice
	子页面中有要展示的内容:图片，文本等信息

##### 学习项目中的配置文件：config.json
<!-- ![QQ截图20210910164007](https://user-images.githubusercontent.com/74289276/138595865-1321abf0-4a17-4dec-90f3-cc693bb296d7.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595865-1321abf0-4a17-4dec-90f3-cc693bb296d7.png" style="zoom:70%;" />

```json
{
  "app": {
    "bundleName": "com.example.myapplication01",  //包名
    "vendor": "example",  //开发者
    "version": {  //版本
      "code": 1000000,  //开发人员内部使用的版本号
      "name": "1.0.0" //用户能看见的版本号
    }
  },
  "deviceConfig": {}, //应用需要的设备权限
  "module": {
    "package": "com.example.myapplication01", //包名
    "name": ".MyApplication", //当前Hap包的名字
    "mainAbility": "com.example.myapplication01.MainAbility",   //Hap包的入口Ability的名称
    "deviceType": [   //当前项目可以运行的设备
      "phone"
    ],
    "distro": {   //Hap包的描述信息
      "deliveryWithInstall": true,  //表示该Hap包是否支持随应用的安装
      "moduleName": "entry",    //当前Hap包的名称
      "moduleType": "entry",    //当前Hap包的类型，entry表示该Hap包是一个主要的模块，可以单独的安装并运行的
      "installationFree": false
    },
    "abilities": [
      {
        "skills": [
          {
            "entities": [
              "entity.system.home"
            ],
            "actions": [
              "action.system.home"
            ]
          }
        ],
        "orientation": "unspecified",
        "name": "com.example.myapplication01.MainAbility",
        "icon": "$media:icon",
        "description": "$string:mainability_description",
        "label": "$string:entry_MainAbility",
        "type": "page",
        "launchType": "standard"
      }
    ]
  }
}
```

##### 了解程序的运行过程
<!-- ![QQ截图20210910170531](https://user-images.githubusercontent.com/74289276/138595922-70d07989-c81d-425b-a94e-00417cf89ee5.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595922-70d07989-c81d-425b-a94e-00417cf89ee5.png" style="zoom: 80%;" />

#### 第二个入门程序：页面跳转

鸿蒙UI中，提供了两种编写布局的方式：
<!-- ![QQ截图20210910201121](https://user-images.githubusercontent.com/74289276/138595937-6a463608-8beb-40d9-9821-1a1e172f7860.png) -->
<img src="https://user-images.githubusercontent.com/74289276/138595937-6a463608-8beb-40d9-9821-1a1e172f7860.png" style="zoom:80%;" />

实验步骤：

##### 1、编写一个页面（文本 + 按钮）

ability_main.xml的布局文件

```xml
<?xml version="1.0" encoding="utf-8"?>
<DirectionalLayout
    xmlns:ohos="http://schemas.huawei.com/res/ohos"
    ohos:height="match_parent"
    ohos:width="match_parent"
    ohos:alignment="center"
    ohos:orientation="vertical">
    <Text
        ohos:id="$+id:text_helloworld"
        ohos:height="match_content"
        ohos:width="match_content"
        ohos:background_element="$graphic:background_ability_main"
        ohos:text="这是第一个页面"
        ohos:text_size="40vp"
        />
    <Button
        ohos:id="$+id:btn1"
        ohos:height="match_content"
        ohos:width="match_content"
        ohos:text="点击跳转"
        ohos:text_color="white"
        ohos:padding="10fp"
        ohos:text_size="25vp"
        ohos:background_element="blue"
        />
</DirectionalLayout>
```

##### 2、编写第二个页面（文本）

新建第二个页面
![QQ截图20210910202144](https://user-images.githubusercontent.com/74289276/138595950-7e4344ac-49cf-46e8-8c0a-8fa0b148b958.png)
<!-- ![](\笔记图片\QQ截图20210910202144.png) -->

在第二个页面的MainAbility2Slice.java代码中编写布局

```java
	@Override    
    public void onStart(Intent intent) {
        super.onStart(intent);
//        super.setUIContent(ResourceTable.Layout_ability_main2);
        //1.创建布局对象
        DirectionalLayout dire=new DirectionalLayout(this);
        //2.创建文本对象
        Text t=new Text(this);
        //设置内容
        t.setText("第二个页面");
        //设置字体大小
        t.setTextSize(25);
        //设置字体颜色
        t.setTextColor(Color.BLUE);
        //3.把文本对象添加到布局当中
        dire.addComponent(t);
        //4.把布局添加到子界面当中
        super.setUIContent(dire);
    }
```

##### 3、给按钮添加一个跳转

在第一个页面的MainAbilitySlice.java代码中编写按钮的点击事件

```java
public class MainAbilitySlice extends AbilitySlice implements Component.ClickedListener { 
    
    private Button btn;
    
    @Override
    public void onStart(Intent intent) {
        super.onStart(intent);
        super.setUIContent(ResourceTable.Layout_ability_main);
        //1.找到按钮 id
        btn= (Button) findComponentById(ResourceTable.Id_btn1);
        //2.给按钮添加点击事件
        btn.setClickedListener(this);
    }

    @Override
    public void onActive() {
        super.onActive();
    }

    @Override
    public void onForeground(Intent intent) {
        super.onForeground(intent);
    }

    @Override
    public void onClick(Component component) {
        switch (component.getId()){
            case ResourceTable.Id_btn1://页面跳转
                Intent intent = new Intent();
                //包含了页面跳转的信息
                Operation build = new Intent.OperationBuilder()
                        .withDeviceId("")//要跳转到哪个设备上，如果传递一个没有内容的空字符串，表示跳转本机
                        .withBundleName("com.example.myapplication01")//我要跳转到哪个应用上，小括号里面可以填写包名
                        .withAbilityName("com.example.myapplication01.MainAbility2")//要跳转的页面
                        .build();//表示将上面的信息进行打包
                //把打包之后的operation设置到意图当中
                intent.setOperation(build);
                startAbility(intent);
                break;
        }
    }
}
```

## 二、事件

> 什么是事件？常见的事件有哪些？
>
> 事件：就是可以被文本、按钮、图片等组件识别的操作
>
> 常见的事件有单击、双击、长按、滑动...

### 1、单击事件

> 单击事件：又叫做点击事件。是开发中使用最多的一种事件，没有之一。

```java
public class MainAbility2Slice extends AbilitySlice {
    private Button btn;
    private Boolean flag=false;
    @Override
    public void onStart(Intent intent) {
        super.onStart(intent);
        super.setUIContent(ResourceTable.Layout_ability_main2);
        btn= (Button) findComponentById(ResourceTable.Id_bnt2);
        btn.setClickedListener(new Component.ClickedListener() {//通过匿名类部类
            @Override
            public void onClick(Component component) {
                Button button= (Button) component;
                if (flag){
                    button.setText("点击我");
                    flag=!flag;
                }else {
                    button.setText("被点了");
                    flag=!flag;
                }

            }
        });
    }
    @Override
    public void onActive() {
        super.onActive();
    }
    @Override
    public void onForeground(Intent intent) {
        super.onForeground(intent);
    }
}
```
