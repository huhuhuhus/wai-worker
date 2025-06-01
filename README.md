🚀 Wai Worker Node 中文指南

通过运行工作节点并为 WAI Protocol 的分布式 AI 推理系统贡献 GPU 算力，你可以获得 W 积分（W Points）。

这些积分代表了你的贡献，未来很可能会转换成奖励或空投

💻 硬件要求：
        •	✅ Apple M 系列芯片（Apple Silicon）
	
	•	支持 M1、M2、M3、M4 的 MacBook / Mac Mini
 
	•	✅ NVIDIA 显卡（支持计算能力 Compute Capability ≥ 5.0）
示例显卡：
	•	GTX 1050
 
	•	RTX 2060
 
	•	RTX 3070
 
	•	RTX 4080
 
📝 注册并获取 API Key（用于连接 WAI 网络）

	1.	打开 WAI Dashboard，注册你的邮箱账号
 
🔗 官网  ：      https://wai.xyz

	2.	登录后，进入左侧菜单的 API Keys 区域
 
	3.	点击 “Create New Key”（创建新密钥）
 
	4.	复制该 API Key，稍后会用到

💽 软件要求：

	•	推荐驱动（适用于本地 NVIDIA 设备）
	•	CUDA Toolkit： 必须安装 12.4 版本（仅支持该版本）

📌 项目地址

👉 https://github.com/huhuhuhus/wai-worker

🧰 一、系统要求
	
  • 操作系统：Ubuntu 20.04 或更高版本
	•	GPU 驱动：已正确安装并配置 NVIDIA 驱动和 CUDA
	•	Python：Python 3.8+
	•	网络：稳定的互联网连接
 
 🛠️ 二、安装步骤
	
  1. 更新系统并安装依赖
 
 - sudo apt update && sudo apt upgrade -y
 - sudo apt install git python3 python3-pip -y

  2. 克隆项目
 
 - it clone https://github.com/huhuhuhus/wai-worker.git
 - cd wai-worker

  3. 安装 python

 - pip3 install -r requirements.txt

  4. 配置环境变量
   根据项目需求，设置必要的环境变量，例如：

 - export WAI_API_KEY=your_api_key_here

   请将 your_api_key_here 替换为您的实际 API 密钥。

  🎯 三、常见问题解答
	
  -  Q：如何查看我的 W 积分？ ￼
  
  A：您可以登录 WAI 官方网站，使用您的账户查看当前积分。 ￼
  
  -  Q：程序运行后无响应？
  
  A：请检查您的网络连接和 GPU 驱动是否正常工作。
  
  -  Q：如何停止工作节点？ ￼
 
  A：在终端中按 Ctrl + C 即可停止程序。

  📢 四、注意事项
	
        •       确保您的设备在运行工作节点时处于稳定的网络环境中。
	
	•	定期检查项目仓库，获取最新的更新和优化。
 
	•	参与社区讨论，获取更多支持和帮助。
