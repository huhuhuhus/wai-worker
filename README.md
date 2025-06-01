# 🚀 Wai Worker Node 中文指南

通过运行工作节点并为 [WAI Protocol](https://wai.xyz) 的分布式 AI 推理系统贡献 GPU 算力，你可以获得 **W 积分（W Points）**。

这些积分代表了你的贡献，未来很可能会转换成奖励或空投！

---

## 💻 硬件要求

- ✅ **Apple M 系列芯片（Apple Silicon）**
  - 支持 M1、M2、M3、M4 的 MacBook / Mac Mini

- ✅ **NVIDIA 显卡**（支持计算能力 Compute Capability ≥ 5.0）  
  示例显卡包括：
  - GTX 1050  
  - RTX 2060  
  - RTX 3070  
  - RTX 4080  

---

## 📝 注册并获取 API Key（用于连接 WAI 网络）

1. 打开 WAI Dashboard，注册你的邮箱账号  
   🔗 官网：[https://wai.xyz](https://wai.xyz)

2. 登录后，进入左侧菜单的 **API Keys** 区域

3. 点击 **“Create New Key”（创建新密钥）**

4. **复制该 API Key**，稍后会在终端中使用

---

## 💽 软件要求

- 推荐安装最新版 **NVIDIA 驱动**
- 必须安装 **CUDA Toolkit 12.4**（**只支持该版本**）

---

## 📌 项目地址

👉 GitHub： [https://github.com/huhuhuhus/wai-worker](https://github.com/huhuhuhus/wai-worker)

---

## 🧰 一、系统要求

- 操作系统：Ubuntu 20.04 或更高版本  
- GPU 驱动：已正确安装并配置 NVIDIA 驱动和 CUDA  
- Python：Python 3.8+  
- 网络：稳定的互联网连接  

---

## 🛠️ 二、安装步骤

1. **更新系统并安装依赖**

   ```bash
   sudo apt update && sudo apt upgrade -y
   sudo apt install git python3 python3-pip -y
   ```

2. **克隆项目**

   ```bash
   git clone https://github.com/huhuhuhus/wai-worker.git
   cd wai-worker
   ```

3. **安装 Python 依赖**

   ```bash
   pip3 install -r requirements.txt
   ```

4. **配置环境变量**

   ```bash
   export WAI_API_KEY=your_api_key_here
   ```

   请将 `your_api_key_here` 替换为你的实际 API 密钥。

---

## 🎯 三、常见问题解答

- **Q：如何查看我的 W 积分？**  
  A：登录 WAI 官网，使用注册账号查看积分。

- **Q：程序运行后无响应？**  
  A：请检查网络连接以及 GPU 驱动是否正确安装。

- **Q：如何停止工作节点？**  
  A：按下 `Ctrl + C` 即可停止程序运行。

---

## 📢 四、注意事项

- ✅ 请保持稳定的网络连接以持续贡献算力  
- 🔄 定期查看 GitHub 仓库获取最新更新  
- 💬 欢迎加入社区讨论获取支持与帮助！

---

由 **[@huhuhuhus](https://github.com/huhuhuhus)** 整理发布
