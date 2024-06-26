﻿# **準備推出 Responsible AI**

[Microsoft Responsible AI](https://www.microsoft.com/ai/responsible-ai?WT.mc_id=aiml-138114-kinfeylo) 是一個旨在幫助開發者和組織建構透明、可信賴且負責任的 AI 系統的倡議。該倡議提供了開發符合隱私、公平和透明等倫理原則的負責任 AI 解決方案的指導和資源。我們還將探討建構負責任 AI 系統相關的一些挑戰和最佳實踐。

## Microsoft 負責任 AI 概述

![RAIPrinciples](../../../../imgs/05/RAI/RAIPrinciples.png)

**倫理原則**

Microsoft 負責任的 AI 以一套倫理原則為指導，例如隱私、公平、透明、問責和安全。這些原則旨在確保 AI 系統以倫理和負責任的方式開發。

**透明 AI**

Microsoft 負責任的 AI 強調 AI 系統透明度的重要性。這包括提供 AI 模型如何運作的清楚說明，以及確保資料來源和演算法是公開可用的。

**負責任的 AI**

[Microsoft Responsible AI](https://www.microsoft.com/ai/responsible-ai?WT.mc_id=aiml-138114-kinfeylo) 推動負責任 AI 系統的發展，這些系統可以提供有關 AI 模型如何做出決策的資訊。這可以幫助使用者理解並信任 AI 系統的輸出。

**包容性**

AI 系統應該被設計為造福每個人。Microsoft 旨在建立包容性的 AI，考慮多樣化的觀點並避免偏見或歧視。

**可靠性和安全性**

確保 AI 系統可靠且安全至關重要。Microsoft 專注於建構穩健的模型，以保持一致的表現並避免有害的結果。

**AI 的公平性**

Microsoft 負責任的 AI 認識到，如果 AI 系統在有偏見的數據或算法上進行訓練，它們可能會延續偏見。該倡議為開發不基於種族、性別或年齡等因素進行歧視的公平 AI 系統提供指導。

**隱私和安全**

Microsoft 負責任的 AI 強調在 AI 系統中保護用戶隱私和數據安全的重要性。這包括實施強大的數據加密和訪問控制，以及定期審計 AI 系統的漏洞。

**責任與義務**

Microsoft 負責任的 AI 促進 AI 開發和部署中的問責制和責任感。這包括確保開發者和組織意識到與 AI 系統相關的潛在風險，並採取措施減輕這些風險。

## 建構負責任 AI 系統的最佳實踐

**使用多樣化的數據集開發 AI 模型**

為了避免 AI 系統中的偏見，重要的是使用代表各種觀點和經驗的多樣化數據集。

**使用可解釋的 AI 技術**

解釋性 AI 技術可以幫助使用者了解 AI 模型如何做出決策，這可以增加對系統的信任。

**定期審計 AI 系統的漏洞**

定期審計 AI 系統可以幫助識別需要解決的潛在風險和漏洞。

**實施強大的資料加密和存取控制**

AI 系統中的資料加密和存取控制可以幫助保護用戶隱私和安全。

**遵循 AI 開發中的倫理原則**

遵循公平性、透明性和問責制等倫理原則，有助於建立對 AI 系統的信任，並確保它們以負責任的方式開發。

## 使用 AI Studio 來實現負責任的 AI

[Azure AI Studio](https://ai.azure.com?WT.mc_id=aiml-138114-kinfeylo) 是一個強大的平台，允許開發者和組織快速建立智能、前沿、市場就緒和負責任的應用程式。以下是 Azure AI Studio 的一些主要功能和能力：

**開箱即用的 APIs 和模型**

Azure AI Studio 提供預建和可自訂的 API 和模型。這些涵蓋了廣泛的 AI 任務，包括生成式 AI、對話的自然語言處理、搜尋、監控、翻譯、語音、視覺和決策。

**Prompt Flow**

Azure AI Studio 中的 Prompt flow 使您能夠建立對話式 AI 體驗。它允許您設計和管理對話流程，使建構聊天機器人、虛擬助理和其他互動應用程式變得更容易。

**檢索增強生成 (RAG)**

RAG 是一種結合檢索式和生成式方法的技術。它通過利用現有知識（檢索）和創造性生成（生成）來提高生成回應的品質。

**生成式 AI 的評估和監控指標**

Azure AI Studio 提供評估和監控生成式 AI 模型的工具。您可以評估其性能、公平性和其他重要指標，以確保負責任的部署。此外，如果您已建立儀表板，您可以使用 Azure Machine Learning Studio 中的無程式碼 UI 來自訂和生成基於 [Repsonsible AI Toolbox](https://responsibleaitoolbox.ai/?WT.mc_id=aiml-138114-kinfeylo) Python 函式庫的負責任 AI 儀表板和相關評分卡。此評分卡有助於您與技術和非技術相關者分享與公平性、特徵重要性和其他負責任部署考量相關的關鍵見解。

要使用 AI Studio 及負責任的 AI，你可以遵循以下最佳實踐:

**定義你的 AI 系統的問題和目標**

在開始開發過程之前，明確定義您的 AI 系統旨在解決的問題或目標是很重要的。這將幫助您識別建構有效模型所需的資料、演算法和資源。

**收集和預處理相關資料**

訓練 AI 系統所使用的數據的品質和數量會對其性能產生重大影響。因此，收集相關數據、清理數據、預處理數據並確保其能代表您試圖解決的人群或問題是很重要的。

**選擇適當的評估**

有各種評估算法可用。根據您的數據和問題選擇最合適的算法是很重要的。

**評估和解釋模型**

一旦你建構了一個 AI 模型，使用適當的指標來評估其性能並以透明的方式解釋結果是很重要的。這將幫助你識別模型中的任何偏見或限制，並在必要時進行改進。

**確保透明度和可解釋性**

AI 系統應該是透明且可解釋的，以便使用者能夠理解它們的運作方式和決策的形成過程。這對於對人類生活有重大影響的應用程式尤為重要，例如醫療保健、金融和法律系統。

**監控和更新模型**

AI 系統應持續監控和更新，以確保它們隨時間保持準確和有效。這需要持續的維護、測試和重新訓練模型。

總結來說，Microsoft 負責任的 AI 是一個旨在幫助開發者和組織建構透明、可信賴且負責任的 AI 系統的計劃。請記住，負責任的 AI 實施至關重要，而 Azure AI Studio 旨在使其對組織來說變得實用。通過遵循道德原則和最佳實踐，我們可以確保 AI 系統以負責任的方式開發和部署，從而使整個社會受益。

