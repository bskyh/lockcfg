# 门锁配置
其他参数
```
{"class_name": "类名"}
```
类名参考下方

| 门锁类名 | 后台门锁型号 | DLL文件名 | 说明 |
| -------- | -------- | -------- | -------- |
| BiDa5_5     | NHS     | btlock55L.dll |
| BiDa5_6     | NHS     | BTLOCK56.DLL |
| BiDa5_7     | NHS     | btlock73L.dll |
| BiDa5_7_vs     | NHS     | btlock57L.dll |
| BiDa5_7_db     | NHS     | btlock57L.dll | 必达5.7数据库版 请到门锁目录把btlock57.mdb文件拷贝到收银端目录 |
| AiDiEr3_21     | NHS     | MainDll.dll |
| V9     | NHS     | V9RF.dll |
| V9_Y     | NHS     | VKYMRF.dll |
| LS_MF     | NHS     | ICdll.dll | 需要根据门锁软件版本选择ICdll.dll |
| LS_MF_NK     | NHS     | NewICdll.dll |
| LS_MF_NODB     | NHS     | ICdll.dll | 创佳门锁  不连数据库接口  |
| NHS     | NHS     | LockDll.dll |
| Y_XL     | NHS     | katedoor.dll | Y系统门锁 MRFCOM.dll |
| DeAn3_3     | NHS     | LockSDK.dll |
| pro0918     | NHS     | proRFL.dll |
| pro0922	     | NHS     | proRFL.dll | 需要一直开着门锁软件 |
| LingBao4_2	     | VS必达5.7     | LCRFRW_SDK.dll |
| Lock_V19	     | NHS     | Interface.exe |
| T307V9	     | NHS     | libInterfaceT307V9.dll |
| HXE1	     | NHS     | HXLOCKSDK_E1.dll |
| HXE2	     | NHS     | HXLOCKSDK_E2.dll |
| HXE6	     | NHS     | HXLOCKSDK_E6.dll |
| V30DB2_0	    | VS必达5.7     | HNAccessG.dll |
| XV	     | NHS     | - |
| ES200601	     | NHS     | es200601.dll |
| IssueCardV8_0 | NHS | MFDLL.dll |
| IssueCardV10_1 | NHS | MFDLL.dll | 锁号是客房编号  |
| MeiDeLong2010 | NHS | HotelCom.dll |
| V17Y | VS必达5.7 | RwCard.dll |
| K9     | NHS     | K9RF.dll |
| mbt2005 | VS必达5.7 | mbt2005.dll | 需要根据目录下的WORD文档配置ODBC数据源 |
| Lark	     | VS必达5.7     | Larkdll.dll |  Lark2.0-Lark3.0 |
| Lark5	     | VS必达5.7     | Larkdll.dll |  Lark5.0 |
| T307V10	     | VS必达5.7     | libInterfaceT307V10.dll | 锁号是   1_2_17  表示  楼栋1 楼层2 客房17  |
| TongTong	     | 锁助手 | CardEncoder.dll | 通通锁 用卡开门的方式 锁号是MAC地址  112233AABBCC  |
| MF308V3	     | VS必达5.7     | libInterfaceMF308V3.dll | 锁号是   1_2_17  表示  楼栋1 楼层2 客房17  |

配置修改完去前台电脑直接制卡
然后打开软件目录  plugins\lock\类名\readme.txt
复制第三行配置   按下方说明修改
