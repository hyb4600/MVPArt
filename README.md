# MVPArt
[ ![Bintray](https://img.shields.io/badge/bintray-v1.0.1-brightgreen.svg) ](https://bintray.com/jessyancoding/maven/MVPArt/1.0.1/link)
[ ![API](https://img.shields.io/badge/API-15%2B-blue.svg?style=flat-square) ](https://developer.android.com/about/versions/android-4.0.3.html)
[ ![License](http://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square) ](http://www.apache.org/licenses/LICENSE-2.0)

## A New Android MVP Architecture

qq群:301733278 有什么问题可以直接问我

请参阅[传统MVP用在项目中是真的方便还是累赘?](https://gold.xitu.io/post/58b25e588d6d810057ed3659)

> [**master**分支](https://github.com/JessYanCoding/MVPArt/tree/master)
>> **master**分支是一个不含网络层的简易框架,主要通过4个**Demo**介绍本框架的思想,特性以及使用方法,小巧灵活适合已经有一整套现有框架但又需要重构为**MVP**结构的项目  
> [**complete**分支](https://github.com/JessYanCoding/MVPArt/tree/complete)
>> **complete**分支是一个含有网络层的完整框架

## Introduction
* 此框架是一个轻量级框架,比较适合中小型项目,大型项目请使用[MVPArms](https://github.com/JessYanCoding/MVPArms)
* 此框架指在解决传统**MVP**类和接口太多,并且**Presenter**和**View**通过接口通信过于繁琐,重用**Presenter**代价太大等问题
* 传统MVP每个页面对应一个presenter,而大多数presenter只有一两个方法,这样导致存在大量代码寥寥无几的**Presenter**,此框架指在解决复用**Presenter**时需要实现过多多余接口方法的问题,鼓励开发者将相近的逻辑写在一个**Presenter**中,不断重用**Presenter**,减少大量类文件
* 当然很多不同的逻辑都写在一个Presenter中,虽然可以少写很多类,但是后面的扩展性肯定不好,所以这个粒度需要自己控制,但是对于外包项目简直是福音

## Architectural
<img src="https://github.com/JessYanCoding/MVPArt/raw/master/image/Architecture.png" width="80%" height="80%">


## About Me
* **Email**: <jess.yan.effort@gmail.com>  
* **Home**: <http://jessyan.me>
* **掘金**: <https://gold.xitu.io/user/57a9dbd9165abd0061714613>
* **简书**: <http://www.jianshu.com/u/1d0c0bc634db>

## License
```
 Copyright 2017, jessyan

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
