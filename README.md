# 電腦畢業設計springboot基於O2O模式的外帶訂餐系統n10ve9【附源碼+資料庫+部署+LW】
####                         11024229洪彤涵
####                         11024104游芷芸
### 系統的選題背景與意義
選題背景： 隨著網路的快速發展和人們生活水準的提高，外送訂餐已成為現代都市生活中不可或缺的一部分。然而，傳統的外帶訂餐方式存在一些問題，例如訂單處理效率低、配送時間長、食品安全等方面的顧慮。基於O2O（Online to Offline）模式的外帶訂餐系統應運而生。該系統透過網路技術，將消費者與餐廳和配送員進行線上連接，提供高效率、便利、安全的外帶訂餐服務。消費者可透過手機APP或網頁平台選擇菜色、下單支付，並即時追蹤訂單狀態，享受優質的外送服務。

在現代社會中，人們的生活節奏越來越快，外帶訂餐已經成為了一種常見的用餐方式。然而，傳統的外帶訂餐方式存在一些問題，例如訂單處理效率低、配送時間長、食品安全等方面的顧慮。因此，設計一個基於O2O模式的外帶訂餐系統具有重要意義。透過利用網路技術，該系統可以將消費者與餐廳和配送員進行線上連接，提供高效、便利、安全的外帶訂餐服務。消費者只需透過手機APP或網頁平台，選擇菜色、下單支付，並即時追蹤訂單狀態，享受優質的外送服務。

意義： 基於O2O模式的外帶訂餐系統具有重要的意義。首先，它可以提供高效率且便利的外帶訂餐服務。傳統的外帶訂餐方式往往需要電話預訂，訂單處理效率低，容易出現錯單、漏單等問題。而基於O2O模式的外帶訂餐系統透過網路技術，消費者可以透過手機APP或網頁平台直接選擇菜色、下單支付，無需等待電話接通及手動處理。這樣，不僅節省了時間，提高了訂餐效率，還減少了訂單處理中的錯誤和糾紛，提升了用戶體驗。

其次，基於O2O模式的外帶訂餐系統可以提供即時訂單追蹤功能。傳統的外帶訂餐方式往往無法及時告知消費者訂單的配送進度，導致消費者焦慮和不確定。而線上外帶訂餐系統可以即時更新訂單狀態，消費者可以透過手機APP或網頁平台隨時查看訂單的配送進度，了解餐廳和配送員的即時位置。這樣，消費者可以更放心等待外送送達，提升了使用者體驗。

此外，以O2O模式為基礎的外帶訂餐系統還可提升食品安全保障。傳統的外帶訂餐方式往往有食品安全問題，如食材來源不明、衛生條件差等。而線上外帶訂餐系統可以與餐廳合作，要求餐廳提供食材來源證明和衛生檢測報告等，確保食品的安全和品質。同時，消費者可以透過系統的評價和回饋功能，對餐廳和配送員的服務進行評價，促使餐廳和配送員提高服務品質和食品安全意識。

綜上所述，基於O2O模式的外帶訂餐系統在提供高效便捷的外帶訂餐服務、即時訂單追蹤和食品安全保障等方面具有重要意義。它利用網路技術的優勢，為消費者提供了更便利、更安全、更可靠的外送訂餐方式，推動外送產業的發展和提升用戶體驗。這將有助於滿足人們快節奏生活的需求，促進餐飲業的創新和發展，推動城市經濟的繁榮和社會的進步。

### 以上選題背景和意義內容是根據本選題撰寫，非本作品實際的選題背景、意義或功能。各位童鞋可參考用於寫開題選題和意義內容切勿直接引用。本作品的實際功能和技術以下列內容為準。

## 技術棧：
前端Vue：用於建立互動式使用者介面。

後端Java開發語言：使用Java作為後端開發語言。

Spring Boot框架：作為快速開發框架，取代了SSM框架，提供自動設定、快速建置等功能。

MySQL 5.7資料庫：用於資料儲存和管理。

使用Spring Boot，你可以透過依賴管理和自動配置來減少手動配置工作，並使用Spring框架的各種功能，例如依賴注入、面向切面編程等。同時，Spring Boot也提供了建置RESTful API、整合測試和部署的工具和插件，讓開發流程更有效率、更方便。

## 3.3功能需求分析
外帶訂餐系統綜合網路空間開發設計需求。目的是將外帶訂餐傳統的管理方式轉換為在線上管理，完成外帶訂餐管理的方便快速、安全性高、交易規範做了保障，目標明確。外帶訂餐系統可以將功能劃分為管理員功能、使用者功能和商家功能。

（1）、管理員關鍵功能包含對系統首頁、個人中心、使用者管理、商家管理、商品分類管理、美食資訊管理、系統管理、訂單管理等進行管理。管理員用例如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/管理員用例圖1.png)

圖3-1 管理員用例圖

（2）、商家關鍵功能包含對系統首頁、個人中心、美食資訊管理、訂單管理等進行管理。商家用例如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/2.png)

圖3-2 商家用例圖

（3）、用戶關鍵功能包含對首頁、美食資訊、美食資訊、後台管理、購物車、個人中心等進行管理。用戶用例如下：

 ![Image](https://github.com/ZhiYum/springboot/blob/main/3.png)

圖3-3用戶用例圖

## 3.4 系統流程分析
登入模組有許多規則，這些規則是用來限制使用者權限的，使用者進入系統前要進行登錄，登入成功後方可對相關權限的操作。系統登入流程如圖3-4所示:

![Image](https://github.com/ZhiYum/springboot/blob/main/4.png)

圖3-4系統登入流程圖

新增用戶的流程是先查詢新用戶名是否已存在，如已有該用戶名，需重擬用戶名並同時輸入新用戶的其它信息，添加新用戶到數據庫時會先驗證數據是否完整，信息都正確且完整時，返回並刷新用戶列表；資訊不正確時，會返回輸入資訊的那一步。流程如圖3-5所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/5.png) 

圖3-5新增用戶流程圖

## 4.1 架構設計
###  架構設計目標如下：

(1)可行性。系統的開發一定是在架構的設計基礎上。

(2)可靠性。對企事業單位的管理來講，系統的可靠性非常重要，所以對系統架構設計上就必須具備相當高的可靠性。

(3)安全行。由於大量的資料都是儲存在資料庫中，這些資料價值高，所以對系統資料庫的安全性要特別重視。

(4)可擴展性。在原有的技術上增加一些功能，這樣才能逐漸完善系統。

(5)可維護性。在可維護性方面體現在：一是追蹤現有的錯誤，二是導入新功能需求到系統上，以便減少營運成本。

(6)可升級性。系統能夠進行更新迭代，使用戶有更好的上網體驗。

下面我们将根据架构设计原则和目标来建立系统的架构设计模型。将信息系统中对象分层，可分为三层：用户界面层、业务层、数据访问层（如下图4-1所示），再把各层中的一些公共部分提出来：权限管理、异常处理，这样得到包图如图4-2所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/6.png) 

图4-1  系统体系架构图
 
![Image](https://github.com/ZhiYum/springboot/blob/main/7.png)

图4-2  系统功能模块包图

## 4.2 系统架构类图
展开包图，得到类图，它是静态结构图的架构，使各个种类之间的关系，表达了静态联系。系统类图如下图4-3所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/8.png)

图4-3 系统类图

## 4.3 系统整体设计
本课题要求实现优质的外卖订餐系统，就一定要包含有数据库、服务器相联系，从而实现系统的功能运转。系统分为管理员、用户和商家三个角色，主要包括系统首页、个人中心、用户管理、商家管理、商品分类管理、美食信息管理、系统管理、订单管理等功能。本系统的功能结构图如下所示：


![Image](https://github.com/ZhiYum/springboot/blob/main/9.png)
 

图4-4 系统功能结构图

## 4.4数据库设计
### 4.4.1　数据库E-R图
_当前用户量最多的数据库是关系型数据库，属于面向对象系统设计。主要考虑的是怎样去对类映射到关系数据库的二维表上。目前可以采用数据库建模来实现。_

根据功能需求来对系统的e-r图来进行分解得到几种实体，以下为部分实体—关系模型。

商家实体属性图如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/10.png)

图4-5商家实体属性图

用户实体属性图如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/11.png)

图4-6用户实体属性图

美食信息实体属性图如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/12.png)

图4-7美食信息实体属性图

美食信息评论实体属性图如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/13.png)

图4-8美食信息评论实体属性图

美食资讯实体属性图如下：

![Image](https://github.com/ZhiYum/springboot/blob/main/14.png)

图4-9美食资讯实体属性图

## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到外卖订餐系统的导航条，通过导航条导航进入各功能展示页面进行操作；系统首页界面如图5-1所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/15.png)

图5-1 系统首页界面

系统注册：在系统注册页面的输入栏中输入用户注册信息进行注册操作；系统注册界面如图5-2所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/16.png)

图5-2系统注册界面

美食信息：在美食信息页面的输入栏中输入商品名称、食材、店铺名称、最小价格、最大价格进行查询，可以查看到美食详细信息；并进行收藏、添加到购物车、立即购买、赞一下、踩一下、评论操作；如图5-3所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/17.png)

图5-3美食信息详情信息

美食资讯：在美食资讯页面的输入栏中输入标题进行查询，可以查看到美食资讯详细信息；如图5-4所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/18.png)

图5-4美食资讯详情信息

个人中心：在个人中心页面输入个人信息进行更新信息、余额充值操作，并根据需要对我的订单、我的地址和我的收藏进行操作；如图5-5所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/19.png)
图5-5个人中心详情界面

## 5.2 后台模块实现
后台用户登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入操作系统进行操作；如图5-6所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/20.png)

图5-6后台登录界面

### 5.2.1管理员模块实现
管理员进入主界面，主要功能包括对系统首页、个人中心、用户管理、商家管理、商品分类管理、美食信息管理、系统管理、订单管理等进行操作。管理员主界面如图5-7所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/21.png)

图5-7 管理员主界面

用户管理：管理员点击用户管理。在用户页面输入用户账号进行查询、新增或删除用户列表，并根据需要对用户详细信息进行详情、修改或删除操作；如图5-8所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/22.png)

图5-8用户管理界面

商家管理：管理员点击商家管理。在商家页面输入店铺名称、店铺地址，选择是否通过进行查询、新增或删除商家列表，并根据需要对商家详细信息进行详情、修改或删除操作。如图5-9所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/23.png)

图5-9商家管理界面

商品分类管理：管理员点击商品分类管理。在商品分类页面输入商品分类进行查询、新增或删除商品分类列表，并根据需要对商品分类详细信息进行修改或删除操作。如图5-10所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/24.png)
图5-10商品分类管理界面

美食信息管理：管理员点击美食信息管理。在美食信息页面输入商品名称、食材、店铺名称、价格进行查询或删除美食信息列表，并根据需要对美食详细信息进行详情或删除操作。如图5-11所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/25.png)

图5-11美食信息管理界面

系统管理：管理员点击系统管理。在美食资讯页面输入标题进行查询、新增或删除美食资讯列表，并根据需要对美食资讯详细信息进行详情、修改或删除操作；如图5-12所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/26.png)

图5-12系统管理界面

订单管理：管理员点击订单管理。在已完成订单页面输入订单编号和商品名称进行查询或删除已完成订单列表，进行日销量、月销量、年销量、商品销量、类型销量、日销额、月销额、年销额统计，并根据需要对已完成订单详细信息进行详情操作，还可以对已退款订单、未支付订单、已发货订单、已支付订单和已取消订单进行详细操作；如图5-13所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/27.png)

图5-13订单管理界面

### 5.2.2用户模块实现
用户进入主界面，主要功能包括对系统首页、个人中心等进行操作。用户主界面如图5-14所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/28.png)

图5-14 用户主界面

### 5.2.3商家模块实现
商家进入主界面，主要功能包括对系统首页、个人中心、美食信息管理、订单管理等进行操作。商家主界面如图5-15所示：

![Image](https://github.com/ZhiYum/springboot/blob/main/29.png)

图5-15商家主界面
