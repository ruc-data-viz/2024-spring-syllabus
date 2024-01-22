# Data Visualization Spring 2024

## Course Information

**Time**: Monday 6:00pm - 8:50pm

**Location**: BSB-118

**Office Hours**: 5:00-6:00 pm, Mondays before class in BSB 118 or by appointment in Armitage 314

### Instructor Information

**Name**: *Mauro Sanchirico*
**Email**: ms3978@rutgers.edu

## Course Description

This is a one-semester introduction to data management and visualization techniques. While there will be a large focus on the visualization of data, data is rarely ever ready for that. This necessarily means that we also learn how to effectively transform our data. Further, visualization of data in the sciences requires an understanding of the types of data being visualized, the sensors or processes which collected the data, the dimensionality of the data, as well as the characteristics of the important information and any noise that may be present. These practical data visualization issues will also be covered. Depending on student interest, a number of special topics from industry and recent state of the art literature will be covered.
* Visualization of sensor data, to include various radio-frequency and imagery sensors, will be covered.
* Machine learning aided data visualization (i.e., using machine learning for data visualization), to include supervised machine learning for data interpolation and pattern recognition, representation learning for feature discovery and data exploration, and language models for visual question answering.
* Visualization of machine learning results and models (i.e., using data visualization techniques to assess and interpret the results of machine learning models) to include visualization of basic machine learning results, input attributions and so-called "explainable AI" techniques, visualization of machine learning models themselves to learn how they work, and the connection between such techniques and generative AI.

 Students will learn how to use the Python programming language to load and manipulate data in order to tell data-driven stories. The Python programming language along with popular data science packages are used extensively. A review of programming techniques required will be covered. Issues around the impacts that data visualization of machine learning results have on the ethical use of AI and machine learning techniques will be discussed, along with issues around the ethical use of AI and machine learning techniques for data visualization and other scientific and engineering applications.

### Prerequisite Knowledge

Students should be comfortable with basic computer programming concepts and undergraduate level mathematics. While students are not expected to be Python experts, they are expected to be able to pick up the necessary skills for this course. *This is a hands-on, coding heavy course*. Mathematically, students should be well versed in the basics for algebra, linear algebra, and more. Familiarity with calculus and differential equations will aid in understanding of some techniques, but in depth knowledge of calculus will not be evaluated in this course. A background in machine learning is not required. Machine learning topics will range from basic to recent state of the art publications, depending on student interests.

### Grading Policy

The semester will use the following grading scheme.

* 10 quizzes: 15%
* 7 homework assignments: 45%
* 1 midterm examination: 20%
* 1 final project: 20%

Assignments and quizzes cannot be made up if missed, with exceptions given only on a case-by-case basic. If you have a personal issue and need an extension, please email me at ms3978@rutgers.edu.

#### Final Grades

Letter grades are assigned as follows:

* `89.5 - 100.0` = `A`
* `86.5 - 89.49` = `B+`
* `79.5 - 86.49` = `B`
* `76.5 - 79.49` = `C+`
* `69.5 - 76.49` = `C`
* `59.5 - 69.49` = `D`
* `00.0 - 59.49` = `F`

#### Extra Credit

There will be a handful of opportunities for extra credit, potentially to include student research in special topics mentioned in the course description. Any point(s) awarded are applied directly to your final grade, up to a maximum of 4 points.

### Course Outline

Our week-to-week is organized as follows, though it is subject to change depending on class pace. Below `A#` refers to when assignments are given and `Q#` refers to when quizzes are given:

* **09/11**: Course Introduction, Course Tools, Basic Python Programming, `Jupyter`
* **09/18**: More Python Programming (A1)
* **09/25**: Introduction to `NumPy`, `pandas` (Q1)
* **10/02**: More on `NumPy` and `pandas` (A2, Q2)
* **10/09**: Loading and cleaning data (Q3)
* **10/16**: Transforming and aggregating data, basic visualizations (A3, Q4)
* **10/23**: Visualizing data with `holoviews`, Midterm
* **10/30**: More on `holoviews`, plot types, basics (A4)
* **11/06**: ~~Composing elements~~ (Q5)
* **11/13**: Variate Data, Correlation, Fitting (A5, Q6)
* **11/20**: Interactive Visualization (Q7)
* **11/27**: Geographic Data Visualization (A6, Q8)
* **12/04**: Brotherly Shove (A7, Q9)
* **12/11**: Real-time Data Streaming (Q10)
* **12/18**: Final Projects Due

## Ethical Use of AI Technologies and Large Language Models

Large Language Models (LLMs), e.g., ChatGPT, and other AI technologies are powerful tools that are accessible to all. While you are not explicitly prohibited from using these tools to facilitate and enhance your learning experience, **you are strictly prohibited from using these tools to perform your work for you**.

Using these tools to complete assignments and/or assigned tasks is unproductive for learning and indicates a insufficient knowledge of the core material required to properly review the outputs of those AI tools for accuracy and safety. Understanding core material before applying AI to help expedite generation of tools and results is a key tenet of the ethical use of AI in industry and academia.

To elaborate on this, we will (repeatedly) make an analogy to Veterinary Dentists, and the interests we all have in ensuring those who operate on our pets are qualified to do so! To perform oral surgery on our pets, holding only the qualifications of a veterinarian or only the qualifications of a dentist is insufficient. Both degrees must be held. Similarly, to apply AI for critical applications in science and engineering, practitioners must be experts in *both* the AI techniques being applied, and the domain of application. In our discussions around the ethical use of AI in this course, we will call this the *Veterinary Dentist Law*.

**Using AI technologies in any way which immediately violates the Veterinary Dentist Law or puts you on a trajectory to increase your probability of violating the Veterinary Dentist Law in the future is considered in violation of the academic integrity policy for this course**. If an AI tool is found to be used in such a manner for any work in this course, a grade of 0 will be given for that work. No exceptions will be made.

Example violations of the Veterinary Dentist law include the following.

In this course:
* Use of AI to write code for you. This prevents you from learning how to apply the underlying techniques.

In industry, outside the context of this course:
* Use of AI in a critical application (e.g., medicine) without any team members having knowledge of that application (the team is only qualified in AI, but not in medicine).
* Use of AI in a critical application (e.g., medicine) with *only* knowledge of the application, and no knowledge of AI on the team (the team is only qualified in medicine, but not in AI). In industry, this risk is mitigated through AI training (of humans, not of models in this case!) and standards, the same as training and standards compliance are required to operate heavy machinery.

Always:
* Blind application of AI to a problem and use of results therefrom without researching and citing prior work around that problem. (See the following section on academic integrity.)

## University Policies on Academic Integrity

Principles of academic integrity require that every Rutgers University student:

* properly acknowledge and cite all use of the ideas, results, or words of others
* properly acknowledge all contributors to a given piece of work
* make sure that all work submitted as his or her own in a course or other academic activity is produced without the aid of unsanctioned materials or unsanctioned collaboration
* obtain all data or results by ethical means and report them accurately without suppressing any results inconsistent with his or her * interpretation or conclusions
* treat all other students in an ethical manner, respecting their integrity and right to pursue their educational goals without interference. This requires that a student neither facilitate academic dishonesty by others nor obstruct their academic progress
* uphold the canons of the ethical or professional code of the profession for which he or she is preparing.

Adherence to these principles is necessary in order to insure that:

* everyone is given proper credit for his or her ideas, words, results, and other scholarly accomplishments
* all student work is fairly evaluated and no student has an inappropriate advantage over others
* the academic and ethical development of all students is fostered
* the reputation of the University for integrity in its teaching, research, and scholarship is maintained and enhanced.

Failure to uphold these principles of academic integrity threatens both the reputation of the University and the value of the degrees awarded to its students. Every member of the University community therefore bears a responsibility for ensuring that the highest standards of academic integrity are upheld.

Infractions are not taken lightly and will fully be pursued. For additional information, visit [http://academicintegrity.rutgers.edu/](http://academicintegrity.rutgers.edu/)

## University Policies on Disabilities

Rutgers University welcomes students with disabilities into all of the University's educational programs. In order to receive consideration for reasonable accommodations, a student with a disability must contact the appropriate disability services office at the campus where you are officially enrolled, participate in an intake interview, and provide documentation:

[https://ods.rutgers.edu/students/documentation-guidelines](https://ods.rutgers.edu/students/documentation-guidelines).

If the documentation supports your request for reasonable accommodations, your campus’s disability services office will provide you with a Letter of Accommodations. Please share this letter with your instructors and discuss the accommodations with them as early in your courses as possible. To begin this process, please complete the Registration form at [https://webapps.rutgers.edu/student-ods/forms/registration](https://webapps.rutgers.edu/student-ods/forms/registration).
