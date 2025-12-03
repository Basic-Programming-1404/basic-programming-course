# TA Contribution Guidelines

All TAs are expected to follow these procedures when contributing course materials. This ensures consistency, traceability, and collaboration across all topics.

---

## 🔹 Pull Request (PR) Workflow

1. **Create a branch** for the topic you are working on.  
    Use a descriptive name:
    
    ```
    topic-name-assignment
    topic-name-workshop
    ```
2. **Work in pairs** whenever possible. Collaborate on the content before creating a PR.
3. **Do not merge your own PRs.** Always request a review from at least one other TA.
4. **Specify clearly in your PR title** whether your work is for:
    - **Workshop**
    - **Assignment**
5. **Follow conventional commits.**  
    Use clear commit types such as:
    ```
    feat:, fix:, docs:, refactor:, style:, chore:
    ```
    Avoid vague commit messages — they make tracking work harder.
6. **Be consistent with naming conventions.**  
    Folder names, file names, and markdown files must follow the templates exactly.

---

## 🔹 Lectures / Workshop Content

### 1. Upload lectures to **Google Drive**
- All slides and resources must be uploaded to the designated Google Drive folder for each topic.
- **Use direct download links**, _not view links_, when referencing files inside the repo.

### 📥 How to Generate a Google Drive Direct Download Link
1. Get the file’s share link (the one ending in `.../file/d/<ID>/view`).
2. Extract the file ID from the link.  
    It looks like:
    ```
    https://drive.google.com/file/d/FILE_ID/view
    ```
    → The `FILE_ID` is the long string between `/d/` and `/view`.
3. Create a direct download URL using this format:
    ```
    https://drive.google.com/uc?export=download&id=FILE_ID
    ```
4. Use **this URL** in markdown files and templates in the repo.

---

### 2. Create Files in the Repo

For each topic, create the following files **from templates**:

1. **`5-TASlides.md`**
    - Use the TA Slides template
    - Include _direct download_ links to all relevant slides
2. **`1-Workshop.md`**
    - Use the Workshop template
    - Update links to questions and slides
3. **`0-Overview.md`**
    - Use the Overview template
    - Update:
        - Overview section
        - Covered in this topic section
        - Links to Slides & Materials page you created
        - Additional resources

---

## 🔹 Assignments

TAs responsible for assignments should:
1. Upload all assignment questions and answers to Google Drive.  
    Again, use **direct download links** when referencing them.
2. Create **`2-Assignment.md`** for the topic using the assignment template.
3. Update links in `2-Assignment.md` to point to the uploaded materials.

---

## 🔹 Recommended Folder Structure

```
BasicProgrammingCourse404Assets/
└── Topic/
    ├── AssignmentQuestionsAndAnswer/
    │   ├── Questions/
    │   ├── Answers/
    │   ├── Questions.zip
    │   └── Answers.zip
    ├── ProfessorSlides/
    ├── TASlides/
    └── WorkshopQuestionsAndAnswer/
        ├── Questions/
        ├── Answers/
        ├── Questions.zip
        └── Answers.zip
```

- Keep **Questions** and **Answers** separate for clarity.
- Zip files are optional but recommended for easier download.
- Always maintain this structure for every topic to keep the repo consistent.

---

> [!tip] Tip  
> Before submitting your PR, double-check:
> 
> - File names follow the templates
>     
> - Commit messages follow **conventional commit** standards
>     
> - Links work and use **direct download URLs**
>     
> - All required materials are uploaded and structured correctly
>     

