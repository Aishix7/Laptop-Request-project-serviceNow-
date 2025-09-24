# 💻 Laptop Request – ServiceNow Catalog Item

## 📌 Project Overview
This project is a **Laptop Request Service Catalog Item** built in ServiceNow.  
It streamlines the process of requesting laptops within an organization by replacing manual processes with an automated Service Catalog workflow.  

The catalog item includes:
- Dynamic variables for accurate data collection  
- UI Policies for conditional field behavior  
- UI Actions such as form reset functionality  
- Governance using Update Sets  
- Export/import process to move between ServiceNow instances  

---

## 🎥 Demo Videos
- [Loom Demo 1](https://www.loom.com/share/b65f37a224c24070a5afd61229d85a9f?sid=34cabf3c-6f50-4b1d-8311-9d835ccff6a8)  
- [Loom Demo 2](https://www.loom.com/share/50afe7b1535349429ff7a6ef9753e09e?sid=94dddc49-f0d3-43a6-838c-fea4317806d0)  

---

## 🔄 Workflow

### 1. Update Set
- Created a **Local Update Set** to capture all changes for governance and deployment.  

### 2. Service Catalog Item
- Built a new **Laptop Request Catalog Item**.  
- Added necessary **variables** to capture request details (e.g., laptop type, accessories).  

### 3. UI Policy
- Created **Catalog UI Policies** to make fields dynamic and context-aware.  
- Example: show/hide fields based on user selections.  

### 4. UI Action
- Developed a **UI Action** to reset the form if needed, improving user experience.  

### 5. Export Update Set
- Exported the update set as XML for deployment to other instances.  

### 6. Deployment to Another Instance
- Logged into another instance.  
- Retrieved the **Update Set**.  
- Imported and committed changes.  

### 7. Testing
- Tested the Laptop Request Catalog Item to validate:  
  - Correct variable behavior  
  - Dynamic UI policies  
  - Reset button functionality  
  - End-to-end request submission  

### 8. Conclusion
The Laptop Request Catalog Item successfully streamlined laptop requests, improved user experience with dynamic fields, and ensured smooth deployment through update sets and GitHub versioning.

---

## 📂 Repository Contents
- `laptop_request.xml` → Exported XML of the catalog item and configurations  
- `README.md` → Documentation with workflow and demo links  

---

## 🛠️ Tools & Skills
- ServiceNow (Service Catalog, Update Sets, UI Policies, UI Actions)  
- GitHub (version control, portfolio)  
- Loom (demo recordings)  

---

## 🚀 How to Use
1. Import the provided `laptop_request.xml` into your ServiceNow instance.  
2. Test the catalog item from the Service Catalog portal.  
3. Review dynamic fields, UI actions, and reset functionality.  
