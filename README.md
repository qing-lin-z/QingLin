# QingLin
青邻聊天：多AI群聊与语音交互工具
 
A lightweight, desktop & mobile-friendly chat tool that supports multi-AI group conversations, voice recognition, and flexible chat management—powered by FunAudioLLM/SenseVoiceSmall for voice input.
 
核心功能 | Core Features
🤖 多AI协同交互
- 支持添加多个AI模型（自定义模型标识，适配主流API），创建专属AI群聊房间
- 精准的AI身份管理，避免身份错乱，每个AI保持独立回复风格
- 群聊成员管理：添加/移除AI、禁言指定AI、修改群名称、解散群聊，防止重复添加
 
🎙️ 智能语音识别
- 集成硅基流动 FunAudioLLM/SenseVoiceSmall 语音模型，支持长按录音、松手自动识别
- 识别结果自动填充输入框，可开启"识别后自动发送"，适配手机/桌面端操作习惯
- 支持50+种语言识别，噪声环境下仍保持高准确率
 
🔧 灵活管理与设置
- 聊天记录本地存储，支持清空/导出文本，保护隐私不上传云端
- 个性化参数配置：调节AI回复温度（0-2）、最大长度（512-4096 tokens）
- 简洁设置面板：语音识别开关、群聊发送模式（顺序/并行）、UI交互偏好
 
🛡️ 安全与防误操作
- 重要操作二次确认（删除AI/解散群聊），避免数据误删
- API密钥本地加密存储，不与第三方服务器交互
- 输入验证与异常处理，网络波动时提供重试机制
 
技术栈 | Tech Stack
- 前端框架：HTML/CSS/JavaScript（原生开发，轻量无依赖）
- 语音识别：硅基流动 FunAudioLLM/SenseVoiceSmall
- 存储方案：LocalStorage（本地数据持久化）
- UI设计：响应式布局、Tailwind CSS 风格样式、流畅过渡动画
- 设备适配：User-Agent精准检测，区分桌面/移动设备交互逻辑
 
适配场景 | Usage Scenarios
- 办公协作：多AI同时提供专业意见，辅助文档写作、方案分析
- 学习研究：创建学科专属AI群聊，获取多维度知识解答
- 日常交互：语音输入快速聊天，解放双手（适合烹饪、通勤等场景）
- 开发测试：快速验证不同AI模型响应效果，对比输出质量
 
许可证 | License
本项目采用 MIT 许可证，详见 LICENSE 文件。
 
致谢 | Acknowledgments
- 语音识别能力基于 硅基流动 FunAudioLLM/SenseVoiceSmall 模型
- UI设计参考 Tailwind CSS 设计规范
- 感谢所有为本项目提供反馈的用户
