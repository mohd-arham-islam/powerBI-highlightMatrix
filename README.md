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

### ✅ Option 1: Clone the Repository

If you have Git installed, run the following command in your terminal:

```bash
git clone https://github.com/mohd-arham-islam/powerBI-highlightMatrix.git
```

### ✅ Option 2: Download as ZIP

1. Visit the repository: [https://github.com/mohd-arham-islam/powerBI-highlightMatrix](https://github.com/mohd-arham-islam/powerBI-highlightMatrix)  
2. Click the green **Code** button  
3. Select **Download ZIP**  
4. Extract the contents  
5. Open `The Office.pbix` in **Power BI Desktop**
