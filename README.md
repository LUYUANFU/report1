# 軟體工程報告
### 11124142 呂元福
實驗三、UML靜態建模之類的分析與設計
* 實驗目的

  
通過UML建模過程掌握類的分析與設計方法。

* 實驗環境


PowerDesigner

* 實驗任務


  針對“迷你圖書管理系统”的用例圖(圖1)，開展分析，完成類建模。
* 實驗步驟


分析實驗任務内容，并利用UML完成類的建模並生成對象，主要包括：

1. 定義類（包括類名、属性、操作等）
2. 建模類之间的关系（包含關聯、泛化、依赖、實現等）
3. 構建完整的類图（至少包含抽象類、组合、聚合、多重性、可見性和接口等）
4. 根据類圖，生成系统某一时刻的對象圖


＊　注意：上述誇號中的内容必须體現在圖中，缺一项本實驗得分扣5分；請自行設計類圖和對象圖，注意邏輯。
* 實驗過程


1. 完整的類圖：
* 分析：

上圖總的來說共有六个類，其中分别是User,RegisteredUser,OrdinaryUser,LibraryManager,MailSystem,Library.

其中，MailSystem是接口。User類關聯RegisterUser和OrdinaryReader類，同时這兩個類和User之間也存在聚集關西，LibraryManager和 OrdinaryReader都繼承RegisterUser类。Library

類依赖于RegisterUser和 OrdinaryReader類；LibraryManager還實現了MailSystem接口,又

和Library之間存在组成關西，各個類都設置了一定的可見性，有的定義了一些操作方法。

2. 對象圖:


從上圖可看出有三個對象
