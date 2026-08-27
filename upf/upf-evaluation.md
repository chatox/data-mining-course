# <img src="upf_logo.png" align="right" width="80"/>Rules for course at UPF (2025)

## 1. Grades

Continuous evaluation will be based in the following elements:

* TM: Grade in the mid-term exam: 25%
* TF: Grade in the final exam: 25%
* PS: Average grade in the 9 [practice sessions](../practicum/README.md): 30%
* PP: Grade in the [personal project](../practicum/personal_project.md): 10%
* PE: Grade in the practices exam: 10%

Your grade will be computed as:
* Theory = 0.5 TM + 0.5 TF
* Practices = 0.6 PS + 0.2 PP + 0.2 PE

To pass the course under continuous evaluation, all of the following must be true:

* Practices ≥ 5.0
* Practice exam grade, PE ≥ 5.0
* Theory ≥ 5.0 (there is no minimum grade in either the mid-term or final exam)

If one of the conditions above fails:
* If you fail to pass because of practices (Practices < 5), you will have to deliver additional work
* If you fail to pass because of the practices exam (PE < 5), you will have an oral practices exam.
* If you fail to pass because of exams (0.5TM + 0.5TF < 5), you will have to take the resit exam, and if you pass it you will pass this subject with a 5.0 in the theory grade.

### 1.1. Getting a grade in the practical sessions (PSxx, individual)

To obtain a grade in the practical session, you must:

* Come to the practice session.
   * To justify an absence, send a justification (e.g., medical certificate) **to your practices instructor.**
* Deliver your work within the deadline.
* A grace period of 24 hours after the deadline will be given, with a -2 points penalization.

Extra points might be added to your grade, allowing you to have up to 12 points (instead of 10) in some practice sessions, however **your total practice grade is capped at 10 points.**

Not delivering your work means a zero grade in that session.

:unamused: Do not work alone and isolated during the practice session. You can prevent simple mistakes by talking to someone else. You can work in pairs, but each one should submit their own work individually and the deliverables must be different.

:rage: Do not work in groups of three or more during the practice session. Feel free to exchange ideas with other students, but do not copy from others.

:heavy_check_mark: It is OK to use generative AI for:

* Understanding how to do some operations.
* Understanding mistakes in your code.
* Produce small snippets of code, which you must review before incorporating, but not entire functions. In that case, mark as `#AI` or `#AI (edited)` in your code.

:warning: It is absolutely not OK to feed the practice questions to an AI-enabled assistant for it to do the practice for you, or to generate text responses using an AI-enabled assistant.

:warning: Copying the work from other person/group in your class, are considered by the university as serious misconduct ("*falta grave*"). The instructor will make a case for the university to sanction this serious misconduct, as per the [university regulations](https://seuelectronica.upf.edu/es/regim-disciplinari-dels-estudiants-de-la-universitat-pompeu-fabra), with a **suspension from the university** for a minimum of six months and a maximum of four years.

### 1.2. Getting a grade in the exam

Midterm exams and final exams are individual work.

Not coming to an exam means a zero grade in that test, unless you can justify your absence to the professor (*profesor de teoría*).

:warning: Copying during an exam, knowingly facilitating the copy of others, elaborating, lending, or facilitating instruments for copying during an exam, are considered by the university as serious misconduct ("*falta grave*"). The instructor will make a case for the university to sanction this serious misconduct, as per the university regulations, with a **suspension from the university** for a minimum of six months and a maximum of four years.

## 2. Guidelines for submitting your work

### 2.1. Exams

The exam will usually be with pen and paper.

### 2.2. Practices 

Your code is delivered as a self-contained Python notebook. This notebook should be readable and understandable on its own by a person familiar with the course's topic. Think of the notebook as a report in which you tell a story, and tell that story well and professionally.

Remember to identify the authorship and date of your code, and the generative AI model you used to assist you, if any. Include as many markdown cells between code cells as needed to explain what you are doing and what we are looking at.

Follow good programming practices:

* Familiarize yourself with a coding style such as [PEP 8](https://www.python.org/dev/peps/pep-0008/) and follow it consistently.
* Give your functions and variables informative names that state what they do or what they contain.
* Avoid code duplication.
* Remove unnecessary code.

These are some of the most common mistakes in code, these deduct points from your grade:

1. Delivering code that does not execute from beginning to end; to prevent this, make sure that ``Kernel > Restart and run all`` works in your notebook, because that is how practice instructors review your code
1. Delivering code that runs on an online platform (such as Google Colab) but that does not run when executed as a local notebook, because that is how practice instructors run your code
1. Not including comments explaining how your code works; these are important for practice instructors to properly review your code
1. Including unnecessary code that is not actually used, except if you used that code to understand the data
1. Leaving cells that you were asked to remove when delivering
1. Removing cells that you were not asked to remove; in particular, questions and requests (usually in blue) are used by the instructors to guide their reviewing, do not remove them
1. Including code that does the same thing twice or more (use functions)
1. Giving cryptic names to your variables or functions
1. Using an inconsistent coding style
1. Using code cells to write text intended to be read, instead, use markdown cells for that; the only text you should have in code cells are brief commentaries to understand a piece of code
1. Including plots without a scale or without a label

## 2.3. Personal project

See [personal project](../practicum/personal_project.md)

These are some of the most common mistakes in reports, these deduct points from your grade:

1. Failing to include your name in the first page
1. Exceeding the number of pages
1. Having the required number of pages but with text that has no substance and is just filling up space
1. Including screenshots, instead of exporting the images
1. Including screenshots of tables, instead of writing the table in the document
1. Copy-pasting tables formatted in ASCII
1. Delivering in the wrong format such as .docx
1. Delivering a report that is not understandable or does not look professional at all

## We expect nothing less than top-quality work

Delivering consistently top-quality work takes time and effort, but it can be very rewarding both personally and professionally :sunglasses:

**Check** your answers, your code, and your reports as many times as needed to ensure they are correct. Be particularly careful when incorporating snippets of code generated by AI. 

**Be precise:** use the section numbers (1.1, 1.2, ...) of the notebook to present your results, and refer to sections by their number. If you need to refer to your figures or tables, number them and refer to them by numbers. Do not include ambiguous statements or plots without a scale or a legend. Do not use colors if you do not explain what each color means. State clearly your assumptions and limitations.

**Be careful** with the presentation of your work. For instance, do not use low-quality screenshots, poorly cropped screenshots showing toolbars and window borders. Instead, export and save high-quality images from each application. Do not copy-paste or screenshot tables into a report without making them actual tables.

As a data scientist your reports and code should be (among other things) correct, understandable, pristine, clear, and pleasant to look at. Ensure you set aside enough time to review, improve, and polish your work. Get used to produce top-quality work and it will become a habit.

# 3. Asking questions

If you need help installing software or packages in your computer, please ask your classmates, for instance through the Aula Global's forum. **Teaching staff does not have the bandwidth to debug your installation.**

* Please use the "Notice board" for general questions, and the forums "Questions about theory" and "Questions about practices" for questions on theory and practices. I get the same questions many times by e-mail and that's not helpful for you or for me. So, **unless it's something specific to you, use the forums.**

* Please if you do need to write me or your practice instructors an e-mail because of something specific to you, **include the name of the subject** in your e-mail, and if necessary, the seminar/practice group in which you are. I've well over 100 students this trimester, which makes it harder to remember everybody.

* Please if you do need to write to any instructor an e-mail, **send it from your UPF address**, so we can give it priority and answer it promptly. We may ignore your e-mail if it comes from an e-mail address that is not from the university.

* Feel free to ask me questions in English, Catalan, or Spanish.

To ask for an appointment, send an e-mail to the course's professor. **No appointments will be given in the 72 hours before midterm or final exams.**
