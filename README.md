# vocational-ppt-transcript

一个用于高职/中职备课的 Codex Skill：读取现有PPT、教材和参考资料，生成逐页对应、可直接照读、适合彩印的Word课堂逐字稿。

## 这套Skill记住了什么

- 以PPT页序为主线，不漏页、不乱序。
- 正文只写教师说的话，不夹带教学设计提醒。
- 不安排等待学生回答的互动。
- 对“为什么要生成HEX”“编译和下载有什么区别”等容易被PPT跳过的前置知识主动补足。
- 代码联系硬件现象讲解，特别核对芯片型号、引脚和高低电平条件。
- 输出单一DOCX，封面独立，按PPT页使用彩色隔断，最后渲染检查。

## 安装

把整个 `vocational-ppt-transcript` 文件夹复制到：

`C:\Users\你的用户名\.codex\skills\vocational-ppt-transcript`

重启或刷新Codex后即可自动匹配，也可以在请求中明确写：

`请使用 $vocational-ppt-transcript 帮我备课。`

## 推荐输入

- 最新版PPT
- 教材或课程标准
- 参考教案、MOOC视频或教师补充讲法
- 课时长度、讲授截止页和是否安排实操

仓库设为Private，仅仓库所有者和授权协作者可访问。
