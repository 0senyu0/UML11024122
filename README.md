# 期中報告
## UML類圖，UML中的一種重要圖形，是在面向對象語言用中用來表示一个類。
如下圖所示（它由兩部分組成，類，類之間的關係）：
![期中 drawio](https://github.com/0senyu0/UML11024122/assets/91513668/eca6e66b-ba01-4340-8e3b-e4eae009f41a)
## 類:
### 類是具有相似結構、行為和關係的一組對象的描述符，是面相對象系統中最重要的構造塊。
如下圖所示，就代表一個類:

![類](https://github.com/0senyu0/UML11024122/assets/91513668/b775c1e5-0d95-4496-8ede-8c18c7c28443)

三個格子從上至下分別表示:

類名稱（如果是接口，就使用斜體表示）
類的特性（一般是類的字段和属性，可以没有）
類的操作（一般是類的方法或行為）

符號有以下幾類：
“+”表示public、
“-”表示private、
“#”表示protected
## 類的關係:
### 根據類的不同，可分為6種:
### 1.依賴關係(用虛箭頭表示):
所謂依賴關係，就是構造這個類的時候，需要依賴其他的類，比如，動物依賴水和氧氣，如下圖所示:

![類的依賴關係](https://github.com/0senyu0/UML11024122/assets/91513668/abaebf3a-8367-4eee-9d04-646a38ccbdbd)

### 2.繼承、泛化關係(用空箭頭表示):
繼承(泛化)關係，它指定了子類如何特化父類的所有特徵和行為。
例如:鳥類是動物的一種，企鵝、鴨、大雁是鳥的一種。

![繼承關係](https://github.com/0senyu0/UML11024122/assets/91513668/f7b4d379-2b48-447e-9246-cd71a10a1525)

### 3.實踐關係（用带空心三角形的虚線表示）

一種類與接口的關係，表示類是接口所有特徵和行為的實現。它有兩種表示方法：

第一種，矩形表示法，

頂端有<<interface>>
第一行：接口名稱
第二行：接口方法

![矩形表示法](https://github.com/0senyu0/UML11024122/assets/91513668/045bbb07-8413-4666-9bc8-c7b59b464f8b)

第二種，棒棒糖表示法

圓圈旁為接口名稱
接口方法在實現類中出現

![棒棒糖表示法](https://github.com/0senyu0/UML11024122/assets/91513668/fe0abc0e-8b9e-4f46-8866-18be99908576)

### 4.關聯關係（用實箭頭表示）

所謂關聯關係，就是這個類有一個屬性是其他類。

![關聯關係](https://github.com/0senyu0/UML11024122/assets/91513668/2a6d4d96-63b0-48c4-bb99-192e50d11cee)

### 5.聚合關係（用带空心菱形的實線表示）

聚合關係是關聯關係的一種，是强的關聯關係 ；

特點： 部分對象的生命周期並不由整體對象来管理。也就是说，當整體對象已經不存在的時候，部分的對象還是可能繼續存在的。比如：一隻大雁脫離了雁群，依然是可以繼續存活的。

![聚合關係](https://github.com/0senyu0/UML11024122/assets/91513668/e3d54957-9c2f-427a-bdcc-57348dbcda95)

### 6.組合關係（用带實心菱形的實線表示）

組合關係同樣是關聯關係的一種，是比聚合關係還要强的關係。

特點：在組合中，部分與整體生命期一致，部分與組合同時創建併同時消亡 。比如：鳥語翅膀的關係。

![組合關係](https://github.com/0senyu0/UML11024122/assets/91513668/8d177ab3-824c-4369-93c2-ecf59d5dea06)


參考資料:https://www.zhihu.com/tardis/bd/art/267298708?source_id=1001
