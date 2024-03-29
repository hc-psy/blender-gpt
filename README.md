# Blender GPT Add-on

<p align="center">
<a href="https://www.buymeacoffee.com/ryvn"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a book&emoji=📚&slug=ryvn&button_colour=40DCA5&font_colour=ffffff&font_family=Bree&outline_colour=000000&coffee_colour=FFDD00" /></a>
</p>

Introducing our newly developed Blender Add-on that harnesses the potential of OpenAI's latest GPT-4 (and GPT-3.5) to transform simple prompts into remarkable 3D models and animations. No more hassle of manually modeling complex 3D elements, let AI do the work!

### Key Features

*   **Expanded Multi-Lingual Support**: We're breaking language barriers! Now switch seamlessly between English, Español, 繁體中文 (Traditional Chinese), 简体中文 (Simplified Chinese), or Français. Tailor your Blender experience to the language you're most comfortable with.
*   **Model Selection at Your Fingertips**: Empower your creativity by choosing the right AI model for your project. Whether it's the versatile Chat GPT-3.5 or the advanced Chat GPT-4, pick the one that fits your project's complexity and budget.
*   **Dial Up Your Creativity**: With adjustable creativity levels, you're in the driver's seat. Control how "out of the box" your AI thinks, with settings ranging from very literal (0) to highly imaginative (1). For precision work, we suggest sticking with 0.
*   **Enhanced User Interface**: Enjoy a more intuitive and streamlined interface. Keep track of your chat history, effortlessly manage and view generated codes, and delete them as you wish. It's the OpenAI chat GPT experience, refined and integrated into your Blender workspace.
*   **Optimized Performance**: Experience the blend of speed and reliability. Our latest version offers faster response times and even more robust outcomes, ensuring that your creative flow is always smooth and uninterrupted.
### Medium Report

[Report](https://medium.com/@ryvnollie/blender-x-chatgpt-a-guide-to-the-ai-powered-blender-add-on-cf5766084f8f)

## Manual

<details>
  <summary>English Manual</summary>

## Get Started

Install our Add-on and dive into the limitless realm of AI-powered 3D modeling.

### Prerequisites

Before you begin, ensure you have the following:

- Blender 3.5 or later installed on your system.
- An OpenAI API key. You can obtain one from the OpenAI website. <a href="https://platform.openai.com/account/api-keys">CLICK ME</a>.

### Installation

To install the Blender GPT, follow the steps below:

1. **Download the Add-on**

   Go to the <a href="https://github.com/hc-psy/blender-gpt/releases/tag/lastest">Blender GPT Releases</a> on GitHub and download the latest version's ZIP file.

2. **Install the Add-on in Blender**

   - Launch Blender.
   - Navigate to `Edit > Preferences > Add-ons > Install`.
   - Locate and select the downloaded ZIP file.
   - Click `Install Add-on`.

3. **Enable the Add-on**

   After installation, enable the add-on by checking the checkbox next to `Blender GPT` (Object).

4. **Enter your OpenAI API Key**

   Go to the Addon preferences menu, paste your OpenAI API key, and choose your preferred language.


### Usage

Follow the steps below to make the most out of the Blender GPT:

1. **Open the Sidebar in 3D View**

    In the 3D View, press `N` to open the sidebar. You will find the `Blender GPT` tab here.

2. **Choose the Chat-GPT Model**

    You have the option to select between the gpt-3 (i.e., gpt-3.5) or gpt-4 models in the `chat-gpt model` tab. However, please note that the gpt-4 model can only be selected if you have access to gpt-4 on OpenAI.

3. **Adjust Level of Model Creativity**

    There is a 'creativity' tab that allows you to control the creativity level (from 0 to 1) of the generated results by GPT. By adjusting this setting, you can encourage more novel output by setting a higher value.

4. **Enter Prompt in Input Field**

    Type your commands in plain language, either in English or Chinese, in the input field, e.g., "create 500 cubes in random locations".

5. **Submit Command**

    Click on the `Submit prompt` button. This action will generate and execute the Blender Python code based on your provided prompt.

6. **Review Generated Codes**

    By clicking on the text icon next to `GPT>`, you can view the Python code generated by the chatgpt model. If you're familiar with script writing, you can further edit this Python code for finer control. In case the generated code is of subpar quality, you can tweak it directly and rerun the execution.

7. **Deletion Options**

    There are two ways to delete dialogues. The first is to delete the result of the last conversation. In this case, the `Submit prompt` will change to `Regenerate Response` for a fresh output. The second method allows for deleting all dialogue history. This is useful if you prefer that future generated results are not partially based on previous dialogues.

That's it! Now you can enjoy the convenience of the Blender GPT. Remember, Blender GPT requires an active internet connection to function properly, as it relies on OpenAI's cloud services.

</details>


<details>
  <summary>中文使用手冊</summary>

## 開始使用

安裝我們的插件，並深入探索無限的AI輔助的3D模型設計的領域。

### 前提條件

在您開始之前，請確保您具有以下條件：

- 系統上已安裝 Blender 3.5 或更新版本。
- OpenAI API 密鑰。您可以從 OpenAI 網站獲取一個。[點我](https://platform.openai.com/account/api-keys)。

### 安裝

要安裝 Blender GPT，請按照以下步驟操作：

1. **下載插件**

   前往 GitHub 上的 <a href="https://github.com/hc-psy/blender-gpt/releases/tag/lastest">Blender GPT 發布頁面</a>，下載最新版本的 ZIP 檔案。

2. **在 Blender 中安裝插件**

   - 啟動 Blender。
   - 導航至 `Edit > Preferences > Add-ons > Install`。
   - 找到並選擇下載的 ZIP 文件。
   - 點擊 `Install Add-on`。

3. **啟用插件**

   安裝後，通過在 `Blender GPT`（Object）旁邊的選框打勾來啟用插件。

4. **輸入您的 OpenAI API 鍵**

   轉到插件偏好設置菜單並粘貼您的 OpenAI API 密鑰並選擇偏好語言。 

### 使用

按照以下步驟來充分利用 Blender GPT：

1. **在3D視圖中打開側欄**

   在3D視圖中，按 `N` 打開側欄。您將在這裡找到 `Blender GPT` 標籤。

2. **選擇 Chat-GPT 模型**

   您可以在 `chat-gpt 模型` 選項卡中選擇 gpt-3（即 gpt-3.5）或 gpt-4 模型。但請注意，只有在 OpenAI 上有 gpt-4 訪問權限的情況下才能選擇 gpt-4 模型。

3. **調整模型創造力水平**

   '創意度' 選項卡允許您控制 GPT 生成結果的創造力水平（從 0 到 1）。通過調整此設置，您可以通過設定更高的值來鼓勵更多新的輸出。

4. **在輸入欄位輸入指令**

   在輸入欄位中，以簡單的語言（英語或中文）輸入您的命令，例如，“在隨機位置創建500個立方體”。

5. **提交指令**

   點擊 `提交指令` 按鈕。這將根據您提供的提示生成並執行 Blender Python 代碼。

6. **檢查生成的代碼**

   點擊 `GPT>` 旁邊的文字圖標，您可以查看 chatgpt 模型生成的 Python 代碼。如果您熟悉腳本編寫，可以進一步編輯這個 Python 代碼以獲得更細致的控制。如果生成的代碼質量不高，您可以直接進行調整並重新執行。

7. **刪除選項**

   有兩種刪除對話的方式。第一種是刪除上次對話的結果。在這種情況下，`提交指令` 將變為 `重新生成`，以便生成新的輸出。第二種方法可以刪除所有對話歷史。如果您希望未來生成的結果不會部分基於之前的對話，這將非常有用。

就是這樣！現在您可以享受 Blender GPT 的便利。請記住，Blender GPT 需要一個穩定的互聯網連接才能正常工作，因為它依賴於 OpenAI 的雲服務。

</details>
