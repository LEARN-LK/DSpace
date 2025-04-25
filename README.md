![image](https://github.com/user-attachments/assets/39c4b934-85ab-42e8-a2db-d73e041a2794)##  **DSpace 8 Overview and Workflow Description**

### **What is DSpace?**
**DSpace** is an open-source repository software platform used by institutions to store, manage, and share digital content like research papers, theses, dissertations, images, and videos. It is widely used in universities, research centers, and libraries for long-term preservation and easy access to digital assets.

### **Role Descriptions in DSpace 8**
1. **Submitter**: The user who submits items (e.g., theses, research papers) to the DSpace repository for archiving.
2. **Collection Admin**: Manages the submission items within a specific collection, reviews submissions, and ensures they meet the required metadata and content standards.
3. **Community Admin**: Manages collections within a community. They can create new collections and adjust settings at the community level.
4. **Site Admin**: Full administrative rights over the DSpace platform. The site admin can manage users, metadata schemas, permissions, and settings for the entire DSpace instance.

---

# 📘 Full DSpace 8 Workflow Guide with Example Scenario

### ✅ Target: Practice the real-world workflow in [DSpace 8 Demo Site](https://demo.dspace.org/xmlui)

---

## 🎓 **Scenario**

> The university wants to set up a new community for the **Faculty of Science**.  
> Inside that community, a collection called **Final Year Projects 2024** will be created.  
> A student (Submitter) will submit a project. The Collection Admin will review and approve it.

---

1. [Site Admin]()
2. [Submitter](https://github.com/LEARN-LK/DSpace/blob/main/Submitter.md)
3. [Collection Admin]()
4. [Community Admin]()








---

# 📘 Full DSpace 8 Workflow Guide with Example Scenario

### ✅ Target: Practice the real-world workflow in [DSpace 8 Demo Site](https://demo.dspace.org/xmlui)

---

## 🎓 **Scenario**

> The university wants to set up a new community for the **Faculty of Science**.  
> Inside that community, a collection called **Final Year Projects 2024** will be created.  
> A student (Submitter) will submit a project. The Collection Admin will review and approve it.

---

## 🧑‍💼 Step 1: **Login as Site Administrator**

- 📧 Email: `dspacedemo+admin@gmail.com`  
- 🔐 Password: `dspacedemo`  
- 🔗 Link: [https://demo.dspace.org/xmlui](https://demo.dspace.org/xmlui)

---

## 🧱 Step 2: **Create a New Community**

1. Click on your name (top-right) → **My DSpace**
2. On the **right sidebar**, click the **➕ icon** → select **“Community”**
3. Fill in:
   - **Community Name**: `Faculty of Science`
   - **Short Description**: `Research and Academic Work`
   - **Introductory Text**: `This community contains final year projects and publications from the Faculty of Science.`

4. Click **Save**

✅ You now have a top-level community.

---

## 📂 Step 3: **Create a Collection Under the New Community**

1. After creating the community, you'll be redirected to its page.
2. Click **“Add”** → **“Collection”**
3. Fill in:
   - **Collection Name**: `Final Year Projects 2024`
   - **Short Description**: `Undergraduate final year research projects`
   - **License**: Keep default or add custom license

4. Click **Save**

✅ Collection is now created inside `Faculty of Science`

---

## 👥 Step 4: **Assign Collection Admin or Submitter (Optional)**

If user roles were customizable in demo (they are limited), you would:

1. Go to the Collection page
2. Click **“Edit Collection”** (gear icon or action menu)
3. Go to **Roles** tab
4. Assign:
   - **Submitter** role to: `dspacedemo+submit@gmail.com`
   - **Reviewer/Editor** role to: `dspacedemo+colladmin@gmail.com`

> ⚠️ Note: Demo site does not allow actual user-role assignment for security, but this is how you would do it in a real DSpace instance.

---

## 🧑‍🎓 Step 5: **Login as Submitter and Submit an Item**

1. Log out and then log in as:
   - 📧 Email: `dspacedemo+submit@gmail.com`
   - 🔐 Password: `dspacedemo`

2. Go to **My DSpace**

3. In the right sidebar, click the **`+` icon** → select **Item**

4. Under **Create a new item in**:  
   Select → `Faculty of Science → Final Year Projects 2024`

5. Fill the form:
   - **Title**: `AI-Based Traffic Management System`
   - **Author**: `John Doe`
   - **Date**: `2025-04-25`
   - **Abstract**: `A smart traffic solution using computer vision and machine learning.`
   - Upload a sample PDF (optional in demo)

6. Click **Next** → **Review** → **Complete Submission**

✅ The submission is now pending review by the collection admin.

---

## 👨‍🔧 Step 6: **Login as Collection Admin to Review**

1. Log out, log in as:
   - 📧 Email: `dspacedemo+colladmin@gmail.com`
   - 🔐 Password: `dspacedemo`

2. Go to **My DSpace**

3. Under **Workflow Tasks**, you’ll see:
   - `AI-Based Traffic Management System`

4. Click the title → Review metadata → Click **Approve** to publish

✅ Item is now published in the repository under:
> Faculty of Science → Final Year Projects 2024

---

## 🔎 Step 7: **Browse or Search for the Published Item**

1. Go to homepage → Click **Communities & Collections**
2. Navigate to:
   - `Faculty of Science → Final Year Projects 2024`
3. You’ll see:
   - `AI-Based Traffic Management System` by `John Doe`

---

## ✅ Summary Table

| Action                                | Role                          | Account                          |
|---------------------------------------|-------------------------------|----------------------------------|
| Create Community                      | Site Admin                    | `dspacedemo+admin@gmail.com`     |
| Create Collection                     | Site Admin                    | `dspacedemo+admin@gmail.com`     |
| Submit an Item                        | Submitter                     | `dspacedemo+submit@gmail.com`    |
| Review/Approve the Item               | Collection Admin              | `dspacedemo+colladmin@gmail.com` |
| View Item After Approval              | Public or Any Logged-in User  | Any                              |

---

Would you like me to prepare a **PDF version**, or help you try this step-by-step with screenshots?
   
