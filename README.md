# 🎯 Power BI Capabilities: Highlight a Matrix Instead of Filtering

By default, when you select a value from a slicer in Power BI, all visuals get filtered accordingly. However, there are scenarios where you may want to **highlight** relevant data without filtering out the rest — preserving full context while drawing attention to specific items.

This example demonstrates how to do exactly that using a dataset from **_The Office_** TV show.

---

## 📊 Use Case

I’ve created a simple dataset featuring episodes of *The Office* along with IMDb ratings and other details.

The report includes a **Matrix visual** displaying episode ratings by **Season** and **Episode**. The goal is:

> ✅ When a user selects a **Guest Appearance** or **Storyline**, only the relevant episodes are **highlighted** in the matrix — **not filtered out**.

---

## 🖼️ Screenshots

### 🔹 Default View  
Matrix visual showing all episodes and their IMDb ratings:

![Matrix Visual Default](https://github.com/user-attachments/assets/8e3e5104-ef60-4e17-a0b1-5b362ad31ac5)

---

### 🔸 Highlighted Selection  
When selecting **"Idris Elba"** as a guest appearance, only the episodes featuring him are highlighted. Color formatting is also applied to distinguish the highlighted values:

![Matrix Visual Highlight](https://github.com/user-attachments/assets/8251cb97-35b1-4210-bd7a-6438f4b7f34e)


---

## 📂 Try It Yourself

You can explore this in the `.pbix` file provided.

> 🔽 **Download Instructions:**  
Clone the repository or download it as a ZIP file and open the `The Office.pbix` file in Power BI Desktop.

---

