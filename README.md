# RUFREE 更新动态 · Updates

RUFREE 面向用户的公开版本说明。

Public, user-facing release notes for RUFREE.

仅展示已审核的公开更新；不代表线上部署状态。

Reviewed public updates only; this is not a live deployment status.

最新公开版本 · Latest public version: **0.1.3-beta38**

机器可读记录 · Machine-readable feed: [updates.json](updates.json)

## 0.1.3-beta38 · 2026-10-31

### Android 消息与贴纸更新汇总

- Android 消息：新增私聊、群聊和课程房，支持未读数、搜索、回复、编辑、删除，以及图片和文件。
- 后台通知：Android 在后台也能接收聊天系统通知，点击后打开对应会话；支持单个会话静音。
- Android 1.2.0：旧版安装时如提示签名不匹配，需要卸载后重装一次；之后的版本可直接更新。
- 自定义贴纸：支持上传、裁剪、发送和收藏贴纸，动图也可保留动画；贴纸会经过内容审核。
- Telegram 贴纸：支持导入贴纸包，也可一次导入多个包，并查看每个包的进度；已添加的包会自动跳过。
- 贴纸面板：新增贴纸包图标导航，点击即可跳转；贴纸消息的时间显示更清楚。
- 贴纸性能：贴纸接近屏幕时才加载、可见时才播放；面板优先显示缓存，改善大量动图时的打开与滚动体验。

### Android Messages and sticker updates

- Android Messages: Direct chats, groups and course rooms now support unread counts, search, replies, editing, deletion, photos and files.
- Background notifications: Android receives chat system notifications in the background. Tap to open the conversation, with per-chat mute controls.
- Android 1.2.0: If upgrading from an older app reports a signature mismatch, uninstall and reinstall once. Later versions can update in place.
- Custom stickers: Upload, crop, send and save stickers, including animated images. Stickers undergo content review.
- Telegram stickers: Import a sticker pack or several packs together, with progress for each pack. Packs already added are skipped.
- Sticker picker: Pack icons let you jump between packs, and sticker message timestamps are easier to read.
- Sticker performance: Stickers load near the screen and play while visible. The picker opens from its cache for smoother loading and scrolling with many animations.

## 0.1.3-beta37 · 2026-10-16

### 日历改版、壁纸与今日简报

- 日历改版：网页版日历的顶部和工具栏重新设计，手机上更紧凑；全天事件单独一行显示，不再让你整天显示忙碌。
- 壁纸：日历和今日页可以设置壁纸，可以选 Glacier 预设，也可以用自己的照片，背景清晰度可以调节，多台设备之间同步。
- 今日简报：AI 今日简报重新设计，更贴近当天的课程和安排；今日页恢复校园相遇，并按日历遮罩显示。
- 提醒更准确：全天事件不再误发上课提醒；同一门课的小幅或个人调整不再反复发送日程更新通知。
- 助手：手机上的布局更紧凑，来源合并显示，对话会自动取标题，支持拖放文件；回答时可以折叠展开思考过程。
- 课表截图：在助手里上传 ACORN 课表截图，可以直接导入课程，并自动填入日期。
- 资料库：课程总览加上课程详情分页；考试时间可以从每门课的 Quercus 通知中读取；可以和同学分享 Quercus 课程订阅。
- 考试日期：通知里公布的考试会替换课表中的对应时段，错误年份的大纲日期不再使用。
- 学期回顾：新增学期成就、故事页和成就墙，并可以分享回顾卡片。
- 个人资料：官方课程卡片和日程洞察已恢复显示。
- 页面切换更流畅：切换页面时先显示骨架屏，回到之前的页面时保留你的状态，不必重新加载。
- 下载与更新：下载页会按你的设备推荐版本；Windows 0.1.4 可以自动检查、下载并安装更新；Mac 应用可以在应用内更新；Android 应用可以检查新版本。
- Apple Watch：新增圆形倒计时表盘小组件，以及两页式手表应用。
- 小组件与平板：iPhone、iPad 和 Mac 都有大号日历小组件；iPad 顶部标签改为胶囊样式；Android 补齐了全部桌面小组件。
- Mac 应用：侧栏、表格和偏好设置页面重新设计，更接近网页版。
- 头像：点击头像可以放大查看。
- 网站：首页标题改为打字机效果，更新日志区块更简洁，关于页面换成新设计；公开页面可以被搜索引擎收录。
- 服务状态：新增公开的服务状态页，可以查看 RUFREE 当前是否正常运行。
- 修复：首页标题加载后跳动、窄屏下日历按钮被遮挡、输入框被键盘挡住、纯文字大纲无法删除，以及 Mac 上 Tab 键无法在登录框之间切换的问题都已修好。

### A new calendar, wallpapers and a rebuilt Today brief

- Calendar redesign: The web calendar header and toolbar are redesigned and more compact on phones. All-day events have their own row and no longer mark you busy all day.
- Wallpapers: The calendar and Today pages can use a Glacier preset or your own photo, with adjustable background sharpness. They sync across your devices.
- Today brief: The AI daily brief has been rebuilt around your classes and plans for the day. Campus encounters are back on Today, hidden behind your calendar.
- Fewer false reminders: All-day items no longer trigger class reminders, and small or personal schedule changes no longer send repeated update notifications.
- Assistant: A more compact phone layout, merged sources, automatic conversation titles, drag-and-drop uploads, and a collapsible view of its thinking.
- Timetable screenshots: Upload an ACORN timetable screenshot in the assistant to import your courses, with dates filled in automatically.
- Library: A course overview with tabbed course pages. Exam times are read from each course’s Quercus announcements, and you can share Quercus course feeds with classmates.
- Exam dates: An exam announced in a notice replaces its timetable slot, and syllabus dates from the wrong year are no longer used.
- Semester recap: Achievements, a story page and an achievement wall, plus a card you can share.
- Your profile shows official course cards and schedule insights again.
- Smoother navigation: Pages show placeholders while they load, and each page keeps its state when you switch away and back.
- Downloads and updates: The download page suggests the right version for your device. Windows 0.1.4 can check, download and install updates; the Mac app updates from inside the app; the Android app checks for new versions.
- Apple Watch: A circular countdown complication and a two-page watch app.
- Widgets and tablets: A large calendar widget for iPhone, iPad and Mac, a capsule tab bar on iPad, and full home screen widget parity on Android.
- Mac app: The sidebar, tables and preference pages are redesigned to match the web app.
- Profile pictures: Tap a profile picture to view it larger.
- Website: A typing headline on the home page, a simpler updates section, a new About page design, and public pages that search engines can index.
- Service status: A public status page shows whether RUFREE is running normally.
- Fixes: The home title no longer jumps after loading, calendar buttons stay visible on narrow screens, inputs are no longer covered by the keyboard, text-only syllabi can be deleted, and Tab moves between sign-in fields on Mac.

## 0.1.3-beta36 · 2026-10-11

### 新网址、全新登录与团队页面

- 新网址：官网和网页版搬到了新的网址，旧地址打开时会自动跳过去，账号和数据都不变。
- 全新登录页：密码登录、验证码登录、找回密码和注册共用同一组输入框，切换时不用重新填写。验证码改成一格一位，输入时有动画，输错会提示并清空，输对自动登录。
- 用验证码找回密码：忘记密码时，输入邮件里的验证码就能设置新密码；也可以直接点邮件里的按钮，在任何浏览器或设备上都能打开。
- 关于我们：新增「关于我们」页面，介绍 RUFREE 的由来和团队成员。
- 更安全的登录：登录、验证码、找回密码和注册加入了 Cloudflare 人机验证，平时自动完成，只有可疑时才需要点一下。
- 公告支持排版：RUFREE 的公告可以带副标题，正文支持小标题、列表、加粗和链接，邮件里也保持同样的排版。
- 首页登录提示：已登录时，首页顶部会滑下一张提示卡，倒计时后进入你的日历；鼠标停在上面可以暂停，也可以关掉留在首页。
- 找回密码邮件的按钮：找回密码邮件里的「继续操作」会打开一个出错的地址，现在可以正常打开。
- 退出登录：点「退出登录」有时会进入登录修复页面，现在会正常退出。
- 未注册的邮箱：用未注册的邮箱请求验证码时，会提示还没有注册，并可以直接用这个邮箱注册，不再显示「仅限邀请注册」。
- 头像显示：换新网址后头像无法显示的问题已经修好。
- 第三方登录和桌面快捷方式：素颜第三方登录和已安装的网页快捷方式会跳到错误地址的问题已经修好。

### A new address, a new sign-in, and the team page

- New address: The website and web app moved to a new address. Old addresses forward to the new one; your account and data stay the same.
- A new sign-in page: Password, email code, password reset and sign-up share one set of fields, so switching keeps what you typed. Codes go into one box per digit with a small animation; a wrong code shakes and clears, a right one signs you in.
- Reset your password with a code: Forgot your password? Enter the code from the email and choose a new one, or press the email's button, which now works in any browser or on any device.
- About us: A new About page tells how RUFREE started and introduces the people behind it.
- Safer sign-in: Sign-in, email codes, password reset and sign-up are protected by Cloudflare's bot check. It runs on its own and asks for a click only when something looks off.
- Formatted announcements: RUFREE announcements can have a subtitle, and their text can use headings, lists, bold and links, in the app and in email.
- Signed-in prompt on the home page: When you are signed in, a card slides down at the top of the home page and opens your calendar after a countdown. Hover to pause it, or close it to stay.
- The reset email's button: The Continue button in password reset emails opened a broken address; it now works.
- Signing out: Signing out sometimes opened the session repair page; it now just signs you out.
- Unregistered email addresses: Asking for a code with an address that has no account now says so and offers to sign up with it, instead of saying registration is invite-only.
- Profile pictures: Profile pictures that stopped showing after the address change are back.
- Third-party sign-in and installed shortcuts: Suyan third-party sign-in and installed web shortcuts no longer jump to a wrong address.

## 0.1.3-beta35 · 2026-10-11

### 通知详情、全新邮件与日历定位

- 通知详情：每条通知都能打开详情页，显示发送者、时间、完整内容、课程、时间和地点，以及下一步可以做什么。
- 跳到日历里的那节课：考试、截止和上课提醒都可以「在日历中查看」，日历会打开那一周并高亮那节课。
- 全新邮件设计：所有 RUFREE 邮件（包括登录验证码）换上冰川风格的新设计，按钮直接打开对应的通知，时间按你所在的时区显示。
- 公告跟随界面语言：公告会显示与你界面语言一致的版本，并注明是否来自 RUFREE 团队。
- 提醒邮件的时间：考试和截止提醒邮件之前显示的是世界协调时间，现在显示你的本地时间。
- 退出登录可能卡住：连续两次退出登录不会再跳到一个打不开的页面。
- 小窗口下的日历顶部：周标题保持一行显示，空间不够时按钮会收成图标。
- 英文上课提醒：下节课、出发、一起上课和换楼提醒补上了英文文案。

### Notification details, new emails, jump to the class

- Notification details: Every notification opens to a page with who sent it, when, the full message, the course, time and place, and the next step.
- Jump to the class: Exam, deadline and class reminders have Show in calendar: the calendar opens that week and highlights the class.
- New email design: All RUFREE emails, including sign-in codes, use the new Glacier design. Their button opens the notification itself, and times are shown in your time zone.
- Announcements in your language: Announcements show the version in your interface language and say whether they come from the RUFREE team.
- Reminder times in emails: Exam and deadline emails showed universal time instead of your local time.
- Signing out could hang: Signing out twice in a row no longer leads to a page that never loads.
- Calendar header on smaller windows: The week title stays on one line, and the buttons fold into icons when space runs short.
- English class reminders: Next class, time to leave, shared class and tight transfer reminders now have English text.

## 0.1.3-beta34 · 2026-10-10

### .de 与 .ca 合并，冰川界面上线

- .de 与 .ca 合并：两边的账号、课表、好友、群组和通知合并到同一套服务。两边都注册过的同一邮箱保留 .de 账号，并补上在 .ca 新增的内容。合并后需要重新登录一次；开启过设备推送的用户，请在设置中重新开启。
- 冰川界面：全新的玻璃质感界面成为默认，仍可在「设置 › 界面风格」切回经典。
- 各平台测试版客户端：官网下载按钮会自动匹配你的设备（Windows、Mac 或 Android 测试版），菜单里可以选择其他版本；iPhone App 即将上架 App Store。
- 猫猫 App 图标：选择猫猫 Logo 样式后，主屏幕、程序坞和标签页图标也会一起换成猫猫。
- .ca 官网入口：.ca 的地址现在显示同一个官网，网页版统一使用 .de 的应用地址；已安装的 App 继续可用。
- 已登录时先提示再进入：官网检测到你已登录时，会先提示并在倒计时后进入日历，也可以选择留在官网。
- 在 App 中更换头像：无论 App 连接哪个服务器地址，都可以正常更换头像。
- 外观选择被重置：选择经典界面或猫猫 Logo 后，刷新不会再被改回默认。

### One RUFREE: .de and .ca merged, Glacier arrives

- .de and .ca merged: Accounts, schedules, friends, groups and notifications from both sides are in one service. Where the same email was used on both, the .de account is kept and what was added on .ca is brought over. Sign in once more; if you had device notifications on, turn them on again in Settings.
- Glacier interface: A new glass interface is the default. Classic stays available under Settings › Interface style.
- Beta clients for every platform: The website’s download button picks the right beta for your device (Windows, Mac or Android), with every version in its menu. The iPhone app is coming to the App Store.
- Neko app icon: Choosing the Neko logo style also switches the Home Screen, Dock and tab icon.
- .ca shows the website: the .ca address now shows the same website, and the web app uses the .de app address. Installed apps keep working.
- Signed-in visitors are told first: When the website sees you are signed in, it says so and opens your calendar after a short countdown, or lets you stay.
- Changing avatars from the app: Avatar changes from the apps work on every server address.
- Saved appearance choices: Classic interface and Neko logo choices no longer revert to the default after a reload.

## 0.1.3-beta23 · 2026-09-29

### 课程资料直达 Assistant

- 课程资料入口可直接开始大纲分析，同时保留先选课程再上传和文档审核的操作。
- 上传的课程资料可以继续在 Assistant 中讨论，无需重复上传。

### Materials opens in Assistant

- Start syllabus analysis directly from Materials, with course-first upload and document review still available.
- Continue discussing uploaded course materials in Assistant without uploading them again.

## 0.1.3-beta22 · 2026-09-28

### 移动端顶栏与导航反馈改进

- 窄屏日历控件可以自动换行，避免按钮被裁切。
- 切换页面时显示渐进加载提示，并在目标页面准备完成后结束。

### Mobile header and navigation improvements

- Calendar controls wrap on narrow screens so buttons remain visible.
- Page navigation shows loading progress until the destination is ready.

## 0.1.3-beta21 · 2026-09-28

### 为课表留出更多空间

- 周视图概览和移动端好友状态默认收起，需要时可展开。
- 日期标题更紧凑，让同一屏可以显示更多课表内容。

### More room for the calendar

- The week overview and mobile friend status start collapsed and can be expanded when needed.
- Compact date headings leave more room for the timetable.
