
##  Step 1: **Login as Site Administrator [1]**

  <img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA1-siteadmin-login.png" alt="image" style="max-width: 100%;width: 500px;">

- 📧 Email: `dspacedemo+admin@gmail.com`  
- 🔐 Password: `dspacedemo`  
- 🔗 Link: [https://demo.dspace.org/xmlui](https://demo.dspace.org/xmlui)

---

##  Step 2: **Create Main Community – Faculty of Science**

1. Click on your name (top-right) → **My DSpace** [2]
 <img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA2-siteadmin-mydspace.png" alt="image" style="max-width: 100%;width: 500px;">
 
2. On the **right sidebar**, click the **➕ icon** [3] → select **“Community”**[4] →  Create **Top Level Community**[5]

<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA3-siteadmin-plus%2B.png" alt="image" style="max-width: 100%;width: 500px;">

<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA4-siteadmin-add-TOP-community.png" alt="image" style="max-width: 100%;width: 500px;">
   
3. Fill in [6]:

<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA5-site-admin-createcommunity.png" alt="image" style="max-width: 100%;width: 500px;">
  
   
   - **Community Name**: `Faculty of Science`
   - **Short Description**: `Research and Academic Work`
   - **Introductory Text**: `This community hosts research outputs, publications, and student projects from the Faculty of Science, including undergraduate and postgraduate work.`

4. Click **Save**

 You now have a top-level community.

###  Step 2.1: Create Sub-Community – Computer Science

1. On the left sidebar, click ➕ → **Community**
2. In the dropdown, **search and select**: `Faculty of Science`
3. Fill:
   - **Name**: Computer Science
   - **Short Description**: Computer Science Projects and Research
   - **Introductory Text**:  
     *This sub-community contains final year projects, thesis submissions, and research publications from the Department of Computer Science.*
4. Click **Save**

---


## 📂 Step 3: **Create Collection – Final Year Projects 2024**

1. After creating the community, you'll be redirected to its page [7].
 <img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA6-siteadmin-created%20community%20page.png" alt="image" style="max-width: 100%;width: 500px;">
   
2. In the **left sidebar**, click the **➕ icon** → select “**Collection** [8]”
<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA7-siteadmin-create-SUB-collection.png" alt="image" style="max-width: 100%;width: 500px;">

   
3. In the dropdown list, search and select: **Faculty of Science** > **Computer Science**[9]

<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA8-siteadmin-select-SUB-communityname.png" alt="image" style="max-width: 100%;width: 500px;">
   
  
4. Fill in [10]:
<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA10-siteadmin-SUB-finalyearcommunity.png?raw=true" alt="image" style="max-width: 100%;width: 500px;">

   - **Collection Name**: `Final Year Projects 2024`
   - **Short Description**: `Undergraduate final year research projects`
   - **License**: Keep default or add custom license

5. Click **Save**

✅ Collection is now created inside `Faculty of Science`

<img src="https://github.com/LEARN-LK/DSpace/blob/main/imgs/SA10-siteadmin-SUB-finulyearcommunity.png" alt="image" style="max-width: 100%;width: 500px;">
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















---

---

### 🔹 Step 5: Assign Roles to the Collection

> **NOTE:** This step is not possible on the public demo site due to permission limits, but is needed in a full installation.

Assign roles (under Collection → ⚙️ Edit → Roles):

| Role | Email | Responsibility |
|------|-------|----------------|
| Submitter | `dspacedemo+submit@gmail.com` | Upload projects |
| Reviewer | `prof.reviewer@uni.edu` | Review/approve |
| Editor | `editor.cs@uni.edu` | Edit metadata |
| Collection Admin | `cs.admin@uni.edu` | Manage collection |
| Community Admin | `faculty.admin@uni.edu` | Manage Computer Science sub-community |

---

### 🔹 Step 6: Configure Workflow

1. Go to Collection → ⚙️ **Edit Collection** → **Workflow**
2. Assign:
   - **Step 1 – Review** → `prof.reviewer@uni.edu`
   - **Step 2 – Metadata Edit** → `editor.cs@uni.edu`
   - **Final Approval** → Site Admin

---

### 🔹 Step 7: Submit Research (as Submitter)

1. Log out and log in as:  
   **Email**: `dspacedemo+submit@gmail.com`  
   **Password**: `dspace`

2. Click **My DSpace** → right sidebar ➕ → **Item**

3. In dropdown **select collection**:  
   `Final Year Projects 2024`

4. Fill submission details:
   - **Title**: *AI-Powered Climate Prediction Model*
   - **Authors**: Jane Doe, John Smith
   - **Keywords**: Machine Learning, Climate, AI
   - **Upload File**: PDF

5. Click **Deposit**

---

### 🔹 Step 8: Review & Approve (Reviewer/Editor)

1. Login as reviewer/editor (if roles are allowed in your own DSpace)
2. Go to **Tasks** → see new submission
3. Approve / Edit metadata
4. Once approved, item is archived and visible to the public

---

## ✅ Final Test

- Check the collection: `Computer Science → Final Year Projects 2024`
- See your item listed!

---

## 🧪 Want to Practice Fully?

To assign roles & fully test the workflow:

👉 I recommend **installing DSpace 8 locally**  
Would you like a **step-by-step local installation guide** for Ubuntu/Linux?

Let me know if you'd also like to simulate **review workflows** or use **Vagrant/Docker** for testing!


