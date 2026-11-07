# 超影答题看电视 · 安装教程

> 面向家长的完整安装指南。全程大约需要 15～30 分钟，不需要电脑，一部安卓手机即可完成。

---

## 一、这是什么

「超影答题看电视」是一款专为家长设计的电视管控应用，核心功能：

| 功能 | 说明 |
|---|---|
| ⏱ 每日时长控制 | 例如每天总共 90 分钟，小朋友可以分散着看，看完即止 |
| 🕐 可看时段控制 | 例如早晨不能看、午休不能看、晚上 10 点后不能看 |
| 📺 内容管控 | 可看央视等直播、点播；限制点播分类（可开放科幻/动画/纪录片/历史，屏蔽爱情/动作/恐怖/伦理/短剧等）；支持关键字过滤（如不能看带「杀」字的节目） |
| 🧮 答题休息 | 看一会儿必须做题休息。支持 Web 端自定义题目：四选一、多选、脑筋急转弯、猜字谜、英语填空、成语释义、历史知识、歇后语、对对联、语数外各科题型；支持自己录入，也支持 AI 自动生成 |
| 🔒 防绕过 | 全屏锁定、屏蔽长按 HOME、屏蔽设置键、PIN 门禁（连错 5 次锁 3 分钟） |

> **重要说明**：所有视频资源均为搜集的网络公开资源，仅可用于学习！

> 手机 App 本身也是一个影视工具（B 站缓存提取、在线视频播放、本地音乐播放、投屏播放等）。

---

## 二、安装步骤

### 第 1 步：手机端安装 App 并登录

1. 在安卓手机上安装「超影答题看电视」App；
2. 打开 App，使用**邮箱**注册/登录。

<img width="1080" height="2400" alt="f8515f6cdc3e184c5ee9838bf046e258" src="https://github.com/user-attachments/assets/7b760275-70dc-4918-b5fc-27894b1dc619" />
<img width="1080" height="2400" alt="32e394a5387769fe4e5288321d6f3682" src="https://github.com/user-attachments/assets/9e9b9b70-7b18-4d6a-a83a-0eacc6ece7c4" />
<img width="1080" height="2400" alt="b312466153ea136bb89fb266666b00d3" src="https://github.com/user-attachments/assets/2ee7de24-abd3-477f-bd9b-5637d87f1d16" />
<img width="1080" height="2400" alt="4c1bedc970a0a749e8fe295b9804f9d7" src="https://github.com/user-attachments/assets/acf55e5e-8c4e-4daa-9346-fc6cc75ee273" />


### 第 2 步：打开电视的 ADB 调试

1. 根据自家电视型号，查找开启 ADB（USB 调试）的方法：
   - 常见电视开启方法：<https://42.194.133.137:8787/adb>
   - 找不到就用 AI 问一下：「XX 品牌 XX 型号电视 如何打开 adb 调试」；
2. **实测刚开启 ADB 后，最好把电视重启一次**，否则可能连不上。

<img width="1308" height="864" alt="fb04af56d6bb4ec788464ccabfe1ae0f" src="https://github.com/user-attachments/assets/d83065d8-ae0a-41a6-86c7-983590ca4f5d" />

### 第 3 步：把 App 安装到电视

1. 手机端打开：**设置 → 工具 → 给电视安装应用（ADB）**；
2. 输入电视机的 **IP 地址**（在电视的 设置 → 网络信息 里查看），端口保持默认 **5555**；
3. 点击「**安装本应用**」→「**连接并安装**」，等待完成（约 3～5 分钟，下方有进度显示），一般会自动打开电视端。

> ⚠️ **电视端首次启动要放行「存储权限」**，否则看不了电视。

<img width="1220" height="2712" alt="ed526689a9aba61686c696c476c44e9b" src="https://github.com/user-attachments/assets/240a7e9c-4ce2-4f29-9c51-c1d64dbf5f71" />
<img width="1220" height="2712" alt="e73aca17f49329393bff5067136d28ca" src="https://github.com/user-attachments/assets/d0d45662-3964-40ad-b198-43ef15679b74" />

### 第 4 步：设为电视桌面

1. 在电视端的答题看电视界面，按遥控器**菜单键**（或点右上角设置）；
2. 输入 **PIN 门禁**（方向密码，输错 5 次会锁定 3 分钟）；
3. 进入设置 → **「设为电视桌面」**，选择「答题电视机」。

之后按遥控器 HOME 键、电视开机，都会直接进入本应用。


### 第 5 步：开启防绕过选项（都在电视端设置里）

| 选项 | 作用 |
|---|---|
| **全屏锁定** | 锁定电视端，防止退出应用 |
| **屏蔽长按 HOME 键** | 防止长按 HOME 调出最近任务逃走 |
| **屏蔽设置键** | 遥控器设置键被拦截，走 PIN 门禁（真系统设置需验 PIN） |

<img width="2400" height="1080" alt="00e0fb0ad0c81166121c662df4a22697" src="https://github.com/user-attachments/assets/58c691be-2ec1-4686-8818-dbae25c60de1" />
<img width="2400" height="1080" alt="image" src="https://github.com/user-attachments/assets/7abfe485-e029-4e6f-95c7-cd7bbc5d3ba7" />
<img width="2400" height="1080" alt="a60c6161f17fc48061d1de1ec287a7ef" src="https://github.com/user-attachments/assets/012eacdf-ab1f-4d3b-be61-0c265545d8bd" />
<img width="2400" height="1080" alt="860f6b3abb72cd4350ef81eb28fada42" src="https://github.com/user-attachments/assets/dcf28244-d313-491a-bbb1-bf71cc79980c" />
<img width="2400" height="1080" alt="9abd13b244e81b986b8298b6ee071f90" src="https://github.com/user-attachments/assets/f6c821ef-507e-4f79-82b2-ccb2134aa04e" />
<img width="2712" height="1220" alt="f45b17280753e725a4db114b246466b3" src="https://github.com/user-attachments/assets/8fca4e5d-5d11-4dca-847b-19b08ec33942" />
<img width="2400" height="1080" alt="894e6af93346607ad2ccb4692a646f28" src="https://github.com/user-attachments/assets/38049e73-1a0d-4e12-9844-19e5531dcf5d" />


### 第 6 步（可选·进阶）：卸载电视自带桌面（聚好看）

> **适用**：电视自带「聚好看」的机型（海信、东芝及大部分国产电视）。
>
> ⚠️ **风险提示，务必先读**：
> - 这一步可能导致电视出现异常，需要重启恢复；
> - 操作前请充分了解卸载自带桌面可能带来的影响，**风险自行承担**；
> - 好消息：只卸载「当前用户」，随时可以一条命令恢复（见下）。

**为什么要做**：不卸载的话，电视断电重启后仍会先进聚好看，小朋友也可能从那里绕开管控。

**操作**：手机 App → 设置 → 工具 → 给电视安装应用（ADB）→ 点击「**卸载聚好看**」→ 确定执行。

**想恢复**：同一界面点击「**恢复聚好看**」→ 确定执行，原样装回（数据保留）。


> 💡 进阶：该界面还有「自定义 ADB 命令」输入框，可以直接在电视上执行任意 adb shell 命令，输出会回显在日志区。

**至此安装完成！** 🎉

---

## 三、远程控制与授权

### 绑定电视

1. 手机端**长按 App 图标** →「我的积分」→ 打开管理网页（自动登录）；
2. 找到「**我的电视**」→「电视列表」→ 输入**电视屏幕上显示的电视码**（播放界面顶部可见），绑定。

### 兑换授权

1. 选择需要的时长（如 30 天 / 60 天授权），扣除相应积分后自动获得授权；
2. 积分需要充值获得（在「积分充值」入口）；
3. 电视端会自动刷新获得授权（播放界面顶部会显示剩余天数）。

### Web 端能配置什么

- 可观看的电视分类、时段、每日时长；
- 锁屏密码、出题频率、禁止播放配置；
- 电视端「临时申请延长」的回复；
- 电视机自定义背景图片；
- 查看电视机播放历史、收藏记录等。
<img width="1220" height="2712" alt="image" src="https://github.com/user-attachments/assets/be6af2f4-832c-47d7-9493-aada4b69b6d9" />
<img width="1220" height="2712" alt="f7ee8f3d2178c1cc03a39b91a894a634" src="https://github.com/user-attachments/assets/729a56fc-8244-4691-b449-d522b56e0b7b" />
<img width="1220" height="2712" alt="d25379203236f28e721ab103e09d4677" src="https://github.com/user-attachments/assets/6641cf04-5cbe-40f9-a142-2e0ee719ccb4" />
<img width="1220" height="2712" alt="c2cee4e49d86de89033886666de48938" src="https://github.com/user-attachments/assets/244b296a-1b08-4543-b79b-1afc6be07190" />
<img width="1220" height="2712" alt="0f010386cb845f5e750772d42e91fd48" src="https://github.com/user-attachments/assets/46ec66be-3eba-4150-b3c8-ca9c589a1668" />
<img width="1220" height="2712" alt="970ad91954b62db83b4b4f531d039af4" src="https://github.com/user-attachments/assets/4b3228ea-981b-448e-bcef-d8e62df3f0a8" />
<img width="1220" height="2712" alt="3a40609352351e74929071ce99651d81" src="https://github.com/user-attachments/assets/7f0ee12e-26c7-47b4-95dc-bf7a191c2828" />
<img width="1080" height="2400" alt="a303239f41c2ddbdef37a96b2c84cd74" src="https://github.com/user-attachments/assets/897f7d57-4f4c-46f2-91fa-062964c92765" />
<img width="1220" height="2712" alt="dbf9e0dcbc280285a1aca31170ba9204" src="https://github.com/user-attachments/assets/2ed8b052-d53e-408e-9730-cacb1d80ecaa" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/bd946511-32fd-4488-9f79-67743f32dfbb" />
<img width="1220" height="2712" alt="image" src="https://github.com/user-attachments/assets/fcbff132-7360-4069-9f8a-f559d83ea59b" />


---

## 四、常见问题（FAQ）

**Q：手机连不上电视？**
- 确认电视 ADB 已打开，且开完**重启过电视**；
- 确认手机和电视在**同一局域网**；
- IP 填电视「网络信息」里的地址，端口 5555；
- 弹「允许 USB 调试」时勾选「一律允许」→ 允许。

**Q：电视上点了安装没反应 / 进度卡住？**
- 等待 3～5 分钟；电视端弹出的安装确认框要允许。

**Q：电视端打开后黑屏 / 看不了电视？**
- 去电视端 App 的应用信息里放行**存储权限**。

**Q：重启后又进了聚好看？**
- 完成第 6 步（卸载聚好看）。

**Q：忘记了电视端设置的 PIN？**
- 连续输错 5 次会锁定 3 分钟；PIN 可在 Web 端配置，忘记可登录网页端查看/修改。

**Q：以后更新电视端版本，ADB 授权弹窗点不了？**
- 先进入电视端设置界面再操作（设置界面不会拦截 adb 授权弹窗）。

---

## 五、兼容性说明

- 作者家中只有海信类电视，实测基于海信；其他品牌方法类似，欢迎反馈补充。
