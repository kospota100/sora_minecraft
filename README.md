
# sora_minecraft

用來存放各種跟Minecraft有關的東西

## 檔案樹 File Tree
```
               File Tree
 =====================================
+ file
    + coordinates                           - 座標的紀錄
        + overworld                         - 主世界
            010_text__文字資料.csv      - 用文字紀錄的座標與座標內容
            011_text__文字資料.xlsx     - 用文字紀錄的座標與座標內容
        + the_nether                        - 地獄
            [與上面目錄相同]
        + the_end                           - 終界
            [與上面目錄相同]
    + maps                                  - 世界地圖、各區域設施地圖
        < planning >
    area_introdution.md                     - 區域一覽                      
    building_list.md                        - 建築一覽
    memo.md                                 - 備忘錄
    todo_list.md                            - 待辦清單    
    + backup                                - 地圖備份
        + saves
```

---

## 示意圖表
```
圖1. 座標示意圖

                        z
                        ^

                  II    3      I
                        |
                        |
      -x <  -3 ======= 0,0 ======= 3  > x
                        |
                        |
                 III   -3     IV

                        v
                        -z

---

圖2. 方位示意圖

    NW                 N                NE
        ------------------------------
        |                            |
        |              z             |
        |              ^             |
        |              |             |
        |              |             |
      W |   -x  <<--- 0,0 --->> x    | E
        |              |             |
        |              |             |
        |              v             |
        |             -z             |
        |                            |
        ------------------------------
    SW                 S                SE

---
```
