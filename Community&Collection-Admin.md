## 🧭 Understanding Community and Collection Admin Roles in DSpace 8

In **DSpace 8**, roles are designed to distribute responsibility while maintaining proper control over content. Two important roles in this system are **Community Administrator** and **Collection Administrator**. Here's what each role can (and can’t) do — explained simply.

---

### 👤 Community Administrator

The **Community Admin** helps manage a section of the DSpace repository — known as a *community*. This could be something like a **faculty, department, or research unit**.

Here’s what a Community Admin can do:

- **Create sub-communities** within their community — for example, adding a department under a faculty.
- **Create and manage collections** that live within their community.
- **Update community details** like names, descriptions, and even upload a logo.
-  **Assign roles** within their community — they can choose who manages sub-communities or collections.
-   *Oversee and review submissions** made to any collections under their control.

However, there are some limits:

- **They can’t create user accounts (E-People)** — only Site Admins can do that.
-  **They don’t have access to global settings or system-level configurations** — that’s also reserved for the Site Admin.

---

### 📁 Collection Administrator

The **Collection Admin** is in charge of a specific *collection*, such as a **group of student theses or a journal's published articles**.

Here’s what a Collection Admin can do:

- **Edit collection details** — including the title, description, and licensing terms.
-  **Manage the submission workflow** — they can assign Submitters, Reviewers, Editors, or Final Editors.
-   **Approve or reject submissions** during the workflow process.
-    **Edit items** in the collection after they’re submitted.
-     **Control access settings** — deciding who can view the collection or individual items.

But they’re also limited in scope:

- **They can’t create new collections** — only Community Admins can do that.
-  **They can’t create or manage user accounts** either.

---

### 🧾 Quick Comparison Table

| What They Can Do                 | Community Admin | Collection Admin |
| -------------------------------- | --------------- | ---------------- |
| Create sub-communities           |  Yes            |   No             |
| Create collections               |  Yes            |   No             |
| Assign and manage workflow roles |  Yes            |   Yes            |
| Moderate or review submissions   |  Yes            |   Yes            |
| Edit metadata and descriptions   |  Yes            |   Yes            |
| Assign admins for sub-sections   |  Yes            |   No             |
| Create user accounts (E-People)  |  No             |   No             |
| Access global site configuration |  No             |    No            |

