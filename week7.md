### **Q1. 當我們揮手控制 DronePaint 中的無人機時，哪些資訊是被電腦「看見」並轉化成動作的？請用自己的話解釋手勢辨識背後的機制流程。**
攝影機捕捉手部的影像，並識別出手上幾個重要的節點位置，比如手指、手腕等。接著，系統會追蹤這些節點的移動軌跡，辨識手部的動作。根據手部動作，電腦將其轉換成對無人機的指令，再由無人機進行執行。
### **Q2. 請列出 DronePaint 至少 3 個技術組件（如 DNN、影像偵測模組等）及它們各自的角色，並說明這些模組若缺失，系統會如何受影響？**
深度神經網絡（DNN）負責識別使用者的手勢，並將其轉化為無人機的控制指令。若缺少 DNN，系統將無法正確識別手勢，無人機的控制會變得不準確，甚至無法響應使用者的操作。影像偵測模組通過攝像頭和影像處理技術捕捉並分析手部動作。如果沒有這個模組，無人機將無法看見並追蹤手勢，從而導致無法準確地控制無人機。避障系統利用感應器來識別並避免周圍的障礙物，保證無人機的安全飛行。若缺失避障系統，無人機將無法有效識別障礙物，增加碰撞風險，影響表演的安全性和流暢度。
### **Q3. 假設 DronePaint 要擴充成大型戶外表演，你認為在哪些方面需做出技術升級或安全強化？**
我認為電腦應有安全機制，避免無人機進行可能造成危險的操作，在電腦辨識出的手勢指令可能造成危險時，能夠拒絕手勢的指令。
### **Q4. 與鍵盤滑鼠或手機觸控相比，你認為手勢控制有何優勢？是否有明確的限制與場景？**
我認為手勢控制的優勢是，手勢控制相較於滑鼠或手機觸控更加直觀與靈活；而我認為其限制是較難利用手勢進行精確的控制，且使用手勢控制比起鍵盤滑鼠或手機觸控，較難長時間維持。
### **Q5. 如果你是藝術創作者，如何利用 DronePaint 的光繪效果來傳達特定社會議題？請設計一個主題與創作構想。**
我認為可以利用 DronePaint 的光繪效果來傳達城市聰的光害議題，通過在有光害與無光害的地方進行相同的光繪來對比，引發大眾的重視。
### **Q6. 在你觀看 DronePaint 示範影片的過程中，有哪些你認為可以改進的地方？若由你擔任 PM，你會提出什麼優化方案？**

