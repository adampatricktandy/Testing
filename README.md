# Pivot Trait

*Pivot Trait helps users identify language that may be negatively interpreted by institutions, and gives the user control on how to reframe that language in a more positive light.*

---

## 🔹 Overview

**Pivot Trait** is an application that helps amplify an individual’s professional potential by translating their unique thinking into powerful, polished language. Our application is purpose-built for individuals who struggle to navigate rigid professional and academic standards. By scanning an individual’s drafts, the application helps to reframe perceived limitations into powerful, actionable phrases—amplifying one’s unique traits so they become competitive advantages for colleges, employers and scholarship boards.

### 👥 Group Members
* Adam Tandy
* Lulu Day
* Clinton Hawkins
* James Mczynski

---

## 🔹 Research and Background

*(Insert your research and background details here if needed)*

---

## 🔹 Project Dependencies

Our project uses a collection of custom language datasets that support text enhancements. This dataset consists of a dictionary that contains alternative words and phrases designed to improve the clarity, professionalism, and readability while not changing the original meaning of the user's writing. 

This system includes both general-purpose and specialized dictionaries for different communication and learning styles, such as **ADHD, Autism spectrum, and dyslexia-focused support**. These are used by the text processing engine to find phrases and words that can be improved and give suggestions to create clearer writing.

---

## 🔹 Configuration, Installation, and Execution Instructions

1. Download both the `Pivot Trait (Master).py` file from this repository as well as any of our sample text documents (or use your own) into a new folder on your computer.
   > [!IMPORTANT]
   > Make sure that all of the files are in the same folder when running the program.
   * `adhd_college_essay_test.txt`
   * `autism_college_essay_test.tx`
   * `dyslexia_college_essay_test.txt`
   * `neurotypical_professional_college_essay_test.txt`
   * `keyword_test.txt`
2. Open python and open the `Pivot Trait (Master).py` file.
3. Run the program.
4. **Welcome to the Pivot Trait Title Screen**
   * Enter your name.
   * Select your strength profile to more accurately reflect your personality and emphasize your traits.
   * Press **Submit** or the **Enter** key.
5. **Upload Screen**
   * Select **Upload File** to open the file explorer.
   * Choose one of our sample text files or provide your own.
   * *Note: only `.txt` files are currently accepted*.
6. **Review/Edit Screen**
   * Here you will see a working copy of your document.
   * The suggested replacement will be highlighted and you will be shown information and provided with a few options:
     * **Commit ‘suggested word’**: This will substitute the highest rated suggestion as shown.
     * **Bypass Edit**: This will skip this edit, either if you are happy with the current word or if you want to skip for now to see how the rest of the document revisions/suggestions work out.
     * **Use Custom**: This will allow you to substitute in whatever custom replacement you provide in the input field. *Note: there are additional suggestions at the bottom of the screen, to use these you must type them in as custom replacements.*
   * Continue working through the edits in your document. You can keep track of progress through the counter at the top.
7. **Final Document Screen**
   * Here you have a chance to review the final document.
   * You can also save the document by pressing the **Save Document** button.
   * Or you can simply exit the program.
   * *Note: if you exit the program all replacements/changes will be lost.*

---

## 🔹 Sample Use-Cases

* Running the file brings you to the **Welcome** screen.
  * **Step 1:** Click in the enter username field and enter your name.
  * **Step 2:** Next select from 4 different Strength Profiles by clicking one of the available buttons: `Autism Spectrum`, `ADHD`, `Dyslexic`, or `General Professional` *(In this demonstration the ADHD profile was selected)*.
  * **Step 3:** Then click **Submit** to continue.

<!-- Drag and drop welcome screen image here -->

***

* After you hit submit you are brought to the **Upload File** screen.
  * **Step 1:** Click the **Upload File** button to select the file you'd like to have Pivot Trait examine.
  * **Step 2:** Select the file by clicking on it.
  * **Step 3:** Click **Open** to proceed to the next step.

<!-- Drag and drop upload screen image here -->

***

* Next you are taken to the **Review Edit** screen. Pivot Trait displays your document and highlights suggested edits according to your selected Strength Profile.
  * **Step 1:** Select whether you would like to commit the suggested edit, bypass it or enter your own custom edit. These choices are: `Commit`, `Bypass Edit`, or `Use Custom`. If using the `Use Custom` function enter your edit in the field under *"Or type your own custom replacement:"*.
  * **Step 2:** Once you select your choice, the program either updates your document with the changes or proceeds to the next edit.
  * **Step 3:** Continue parsing through your document until you reach the end of the edits. Pivot Trait will automatically move to the next screen after the last edit is displayed.

<!-- Drag and drop review screen image here -->

***

* Next you are taken to the **Final Implemented Document** screen. Pivot Trait applies all of the changes made to your document and displays it in its edited form.
  * **Step 1:** To save your edited document, click the **Save Document** button.
  * **Step 2:** Once you click the **Save Document** button you are taken to the **Save As** screen where you can enter the filename of your edited document.
  * **Step 3:** Save your document by clicking the **Save** button.
  * **Step 4:** After clicking the **Save** button you are taken back to the **Final Implemented Document** screen where you can exit the program by clicking the **Exit Program** button.

<!-- Drag and drop final screen image here -->

---

## 🔹 Table of Files

| Filename | Location | Function | Contributor / Contributions |
| :--- | :--- | :--- | :--- |
| **Master_Save_Function.py** | Main | The final, working program file for Pivot Trait application. | **Adam:**<br>• Implemented underlying skeleton from NeuroTest 1.py.<br>• Introduced File Upload, Get Username, Parsing and Save Document using Tkinter.<br><br>**Clinton:**<br>• Streamlined all areas of application.<br>• Created Strength Profile system with dynamic parameters.<br>• Created all verbiage, button design, and aesthetics for all screens.<br><br>**Lulu:**<br>• Implemented dual dictionary functionality.<br>• Tested, debugged, and fixed grammar issues.<br><br>**James:**<br>• Tested and debugged program with sample documents.<br>• Spearheaded targeted testing campaign.<br>• Examined for bias, accessibility, and inclusion. |
| **adhd_college_essay_test.txt**<br>**autism_college_essay_test.txt**<br>**dyslexia_college_essay_test.txt** | Main | Sample documents created to be uploaded to and tested by program functionality. Each tailored to specific traits inherent in different definitions of neurodiversity. | **James:**<br>• Created all sample files.<br>• Researched traits of Autism Spectrum, ADHD, and Dyslexia to mirror user descriptions.<br>• Ran samples to find limitations or conflicts. |
| **neurotypical_professional_college_essay_test.txt** | Main | Sample document created to convey neurotypical traits. Designed to test limits of program functionality with a profile that doesn't match neurodivergent traits. | **James:**<br>• Created and tested this profile edge-case. |
| **pivot_trait_language_library.py** | Main | Expansive dictionary of descriptors and phrases program scanned document for and selected suggested edits from. | **Lulu:**<br>• Created all entries in dictionary integral to program.<br>• Compiled list of improvable self-descriptors.<br>• Compiled list of suggested edits to transform text into optimized language. |
| **README.md** | Main | File explaining all aspects of program. | **Adam:**<br>• Sample use-cases with screenshots & alt text.<br>• Table of files and contribution map.<br><br>**Clinton:**<br>• Configuration, installation, and execution instructions.<br><br>**Lulu:**<br>• Project dependencies including data libraries.<br><br>**James:**<br>• Important background research, terms, and citations. |
| **About_Test_Files** | Test_Files | Explanation of folder existence. | *(Team Archive)* |
| **NeuroTest 1.py** | Test_Files | First iteration of Pivot Trait program, serving as skeletal architecture. Primitive program used clunky dictionaries to test parsing. | **Adam** (Skeletal build) |
| **Sample.txt** | Test_Files | Primitive, first sample text generated to test terms in library of self-descriptors. | **Adam** |
| **NeuroTest-2LD.py** | Test_Files | Test file of Pivot Trait used in testing and developing language library. | **Lulu** |
