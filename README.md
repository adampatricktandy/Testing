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

---

## 🔹 Project Dependencies

Our project uses a collection of custom language datasets that support text enhancements. This dataset consists of a dictionary that contains alternative words and phrases designed to improve the clarity, professionalism, and readability while not changing the original meaning of the user's writing. This system includes both general-purpose and specialized dictionaries for different communication and learning styles, such as ADHD, Autism spectrum, and dyslexia-focused support. These are used by the text processing engine to find phrases and words that can be improved and give suggestions to create clearer writing.

---

## 🔹 Configuration, installation, and execution instructions

1. Download both the ‘Pivot Trait (Master).py’ file from this repository as well as any of our sample text documents (or use your own) into a new folder on your computer. *Note: make sure that all of the files are in the same folder when running the program.*
   * a. adhd_college_essay_test.txt
   * b. autism_college_essay_test.tx
   * c. dyslexia_college_essay_test.txt
   * d. neurotypical_professional_college_essay_test.txt
   * e. keyword_test.txt
2. Next open python and open the ‘Pivot Trait (Master).py’ file.
3. Run the program
4. **Welcome to the Pivot Trait Title Screen**
   * a. Enter your name
   * b. Select your strength profile to more accurately reflect your personality and emphasize your traits
   * c. Press ‘Submit’ or the ‘Enter’ key
5. **Upload Screen**
   * a. Select ‘Upload File’ to open the file explorer
   * b. Choose one of our sample text files or provide your own
   * *Note: only .txt files are currently accepted*
6. **Review/Edit Screen**
   * a. Here you will see a working copy of your document
   * b. The suggested replacement will be highlighted and you will be shown information and provided with a few options:
     * **i. Commit ‘suggested word’**
       * 1. This will substitute the highest rated suggestion as shown
     * **ii. Bypass Edit**
       * 1. This will skip this edit, either if you are happy with the current word or if you want to skip for now to see how the rest of the document revisions/suggestions work out
     * **iii. Use Custom**
       * 1. This will allow you to substitute in whatever custom replacement you provide in the input field
       * *Note: there are additional suggestions at the bottom of the screen, to use these you must type them in as custom replacements*
   * c. Continue working through the edits in your document
     * i. You can keep track of progress through the counter at the top
7. **Final Document Screen**
   * a. Here you have a chance to review the final document
   * b. You can also save the document by pressing the ‘Save Document’ button
   * c. Or you can simply exit the program
   * *Note: if you exit the program all replacements/changes will be lost.*

---

## 🔹 Sample Use-Cases

* Running the file brings you to the ‘Welcome’ screen.
  * ○ Step 1. Click in the enter username field and enter your name.
  * ○ Step 2. Next select from 4 different Strength Profiles by clicking one of the available buttons: Autism Spectrum, ADHD, Dyslexic or General Professional (In this demonstration the ADHD profile was selected)
  * ○ Step 3. Then click ‘Submit’ to continue.

<img width="383" height="582" alt="Welcome_Screen" src="https://github.com/user-attachments/assets/c4819253-5226-4d74-b203-68b087c96c3f" />


***

* After you hit submit you are brought to the ‘Upload File’ screen.
   ○ Step 1. Click the ‘Upload File’ button to select the file you'd like to have Pivot Trait examine.
   ○ Step 2: Select the file by clicking on it.
   ○ Step 3: Click ‘Open’ to proceed to the next step.

<img width="350" height="487" alt="Upload_File" src="https://github.com/user-attachments/assets/cabba7dd-16ee-4ad0-a096-ceab01bf41ca" />


***

* Next you are taken to the ‘Review Edit’ screen. Pivot Trait displays your document and highlights suggested edits according to your selected Strength Profile.
   ○ Step 1. Select whether you would like to commit the suggested edit, bypass it or enter your own custom edit. These choices are: Commit, Bypass Edit or Use Custom. If using the ‘Use Custom’ function enter your edit in the field under ‘Or type your own custom replacement:’
   ○ Step 2: Once you select your choice, the program either updates your document with the changes or proceeds to the next edit.
   ○ Step 3: Continue parsing through your document until you reach the end of the edits. Pivot Trait will automatically move to the next screen after the last edit is displayed.

<img width="351" height="430" alt="Edit_Screen_1" src="https://github.com/user-attachments/assets/22181d12-12bf-40b1-8228-620e0840f5a1" />


<img width="351" height="430" alt="Edit_Screen_2" src="https://github.com/user-attachments/assets/8c3bd086-8f06-4149-9d68-c07a6f7e1c54" />


<img width="351" height="430" alt="Edit_Screen_3" src="https://github.com/user-attachments/assets/1ebf1855-7741-4100-ac2a-8d5bc258fec7" />


***

* Next you are taken to the ‘Final Implemented Document’ screen. Pivot Trait applies all of the changes made to your document and displays it in its edited form.
   ○ Step 1. To save your edited document, click the ‘Save Document’ button.
   ○ Step 2: Once you click the ‘Save Document’ button you are taken to the ‘Save As’ screen where you can enter the filename of your edited document.
   ○ Step 3: Save your document by clicking the ‘Save’ button.
   ○ Step 4: After clicking the ‘Save’ button you are taken back to the ‘Final Implemented Document’ screen where you can exit the program by clicking the ‘Exit Program’ button.

<img width="360" height="386" alt="Final_Doc_Screen_1" src="https://github.com/user-attachments/assets/1fb1fab4-e2bb-434c-97e2-cb0b5d206c73" />


<img width="358" height="244" alt="Final_Doc_Screen_2" src="https://github.com/user-attachments/assets/e9903991-6f55-4812-9937-2eae06c78917" />


<img width="360" height="386" alt="Final_Doc_Screen3" src="https://github.com/user-attachments/assets/7e18dc97-81d3-4619-84af-40c56260426f" />


---

## 🔹 Table of Files

| Filename | Location | Function | Contributor/ Contributions |
| :--- | :--- | :--- | :--- |
| Master_Save_Function.py | Main | The final, working program file for Pivot Trait application | **Adam:**<br>- Implemented underlying skeleton of program from NeuroTest 1.py.<br>-Introduced File Upload, Get Username, Parsing and Save Document functions using Tkinter filedialogue functionality.<br><br>**Clinton:**<br>-Streamlined all areas of application.<br>-Created Strength Profile system which applied dynamic parameters shaping user experience throughout the program that provides specific “suggested edits” based on profile selection.<br>-Created all verbiage, button creation selection and design aesthetics of ‘Welcome Screen’, ‘Upload File’ screen, ‘Review Edit’ screen and ‘Final Implemented Document’ screen’.<br><br>**Lulu:**<br>-Implemented dual dictionary functionality and all dictionary entries integral to program working and parsing documents correctly.<br>-Tested and debugged dictionary functionality<br>-Updated changes to dictionary following her discovery of grammar issues<br><br>**James:**<br>-Tested and debugged program with sample documents he created.<br>-Spearheaded targeted testing campaign by creating and running sample document specifically designed antithesis of working elements of program<br>-Examined for bias, accessibility and inclusion |
| adhd_college_essay_test.txt<br><br>autism_college_essay_test.txt | Main | Sample documents created to be uploaded to and tested by program functionality. Each tailored to specific traits inherent in different definitions of neurodiversity. | **James:**<br>-Created all sample files<br>-Researched traits of Autism Spectrum, ADHD and Dyslexia and implemented them into sample documents mirroring how user with traits may describe certain personality aspects.<br>-Ran sample documents through program to find limitations, bugs or confilicts |
| dyslexia_college_essay_test.txt<br><br>neurotypical_professional_college_essay_test.txt | Main | Sample document created to convey neurotypical traits. Designed to test limits of program functionality with profile that doesn't match neurodiveregent traits. | *(Text block mapped directly to the sample document metrics above)* |
| pivot_trait_language_library.py | Main | Expansive dictionary of descriptors and phrases program scanned document for and selected suggested edits from. | **Lulu:**<br>-Created all entries in dictionary integral to program functionality<br>-Compiled list of possible, improvable self-descriptors a user might employ when writing document that describes one's personal temperament, peronality and work ethic<br>-Compiled list of suggested edits designed to transform the self-descriptors that positively conveys aspect of personality in professional, optimized language |
| README.md | Main | File explaining all aspects of program | **Adam:**<br>- Sample use-cases with screenshots (including alternative text)<br>-Table of files, their features, who was responsible for/contributed to each<br>-Integrated all submissions into HTML that included formatting and pictures<br><br>**Clinton:**<br>-Configuration, installation, and execution instructions<br><br>**Lulu:**<br>-Project dependencies including third-party libraries and data, if necessary<br><br>**James:**<br>-Important background research, information, and terms<br>-Citations |
| About_Test_Files | Test_Files | Explanation of folder existence | |
| NeuroTest 1.py | Test_Files | First iteration of Pivot Trait program, serving as skeletal architecture from upon which full program was built. Primitive program used clunky dictionaries to test parsing and suggested edit functionlity. | **Adam** |
| Sample.txt | Test_Files | Primitive, first sample text generated to test terms in library of self-descriptors and suggested edits | **Adam** |
