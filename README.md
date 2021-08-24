# COMP790-101: Information Theory

Instructor: [Colin Raffel](http://colinraffel.com)

Term: Fall 2021

Meeting time: Mondays and Wednesdays, 1:25-2:40pm in SN 014

Office hours: By appointment

Information theory is the scientific study of the transmission of information over a possibly lossy channel, or as Shannon put it, "reproducing at one point either exactly or approximately a message selected at another point."
It is a field that has its roots in probability and statistics and underpins many important technologies, such as cryptology, linguistics, and telecommunication.
We will mainly focus on applications in machine learning, thanks to the fact that information theory provides a unified framework for understanding many fundamental concepts in machine learning.
The course will closely follow portions of [Information Theory, Inference, and Learning Algorithms by David Mackay](https://www.inference.org.uk/itprnn/book.pdf).
(Note: The course catalog entry for this course has the description "Permission of the instructor. This course has variable content and may be taken multiple times for credit." which is not terribly descriptive. Please refer to this page for the most up-to-date information.)

## Prerequisites

Students must have some exposure to probability and statistics.
To better understand applications discussed in the class, some knowledge of machine learning will be beneficial.
Finally, students must be proficient in reading and writing Python code.

## Format

**This class will not have a standard lecture/homework/exam format.**
Instead, students will take the primary role in teaching the material to one another.
Specifically, it will be a [Role-Playing Seminar](https://colinraffel.com/blog/role-playing-seminar.html) where each class session, a subset of students will present material from one of a few pre-defined perspectives.
There will be no final project, exams, or other assignments.
Hopefully, this will not only give you a deeper understanding of the material, but also give you some teaching skills along the way.
However, *you should only take this class if you are game for a rather intensive and unusual course format*.

Each class session, we will be covering a (sub)section from the textbook.
A rotating subset of students will then prepare various presentations or other material based on the reading.
The roles and schedule are subject to change depending on the number of enrolled students, but to give you a sense for the format, likely roles will include:
* **Lecturer**: Prepare a ~30 minute lecture on the assigned reading for the class session.
* **Tutor**: Pick one of the exercises from the textbook, prepare a very thorough solution, and present it to the class.
* **Examiner**: Come up with a new exercise that provides a deep test of some of the ideas in the reading.
* **Note taker**: Prepare a clean set of notes on the assigned material.
* **Researcher**: Find a research paper that uses one of the techniques discussed in the reading and prepare a short presentation about how it was used.
* **Hacker**: Implement one of the ideas from the reading in Python code and prepare a short presentation about it.
* **Diagrammer**: Create a diagram of one of the concepts from the reading.

## Schedule

| Date | Content |
|----|----|
| Wed, 8/18 | Course introduction, logistics, background (lecture by Colin) |
| Mon, 8/23 | Binary symmetric channel and repetition codes, pp. 1-8 (lecture by Colin) |
| Wed, 8/25 | Binary symmetric channel and repetition codes, part 2 (lecture by Colin) |
| Mon, 8/30 | Hamming codes, pp. 8-16 |
| Wed, 9/1 | Probabilities and ensembles, pp. 22-26 |
| Mon, 9/6 | Labor day (no class) |
| Wed, 9/8 | Forward and inverse probabilities, pp. 27-32 |
| Mon, 9/13 | Entropy, pp. 32-36 |
| Wed, 9/15 | Information content, pp. 68-73 |
| Mon, 9/20 | Data compression, pp. 73-78 |
| Wed, 9/22 | Shannon's source coding theorem, pp. 78-84 |
| Mon, 9/27 | Symbol codes, pp. 91-95 |
| Wed, 9/29 | The Huffman code, pp. 95-101 |
| Mon, 10/4 | Arithmetic coding, pp. 110-117 |
| Wed, 10/6 | Lempel-Ziv coding, pp. 118-123 |
| Mon, 10/11 | More on entropy, mutual information, and the noisy channel, pp. 138-140 and 146-147 |
| Wed, 10/13 | Noisy channels, pp. 147-151 |
| Mon, 10/18 | The noisy-channel coding theorem sketch, pp. 151-155 |
| Wed, 10/20 | The noisy-channel coding theorem proof part 1, pp. 162-167 |
| Mon, 10/25 | The noisy-channel coding theorem proof part 2, pp. 167-172 |
| Wed, 10/27 | The Gaussian channel, pp. 177-182 |
| Mon, 11/1 | Error-correcting codes, pp. 183-187 |
| Wed, 11/3 | Hash codes, pp. 193-201 |
| Mon, 11/8 | Binary codes part 1, pp. 206-213 |
| Wed, 11/10 | Binary codes part 2, pp. 213-220 |
| Mon, 11/15 | Very good linear codes exist, pp. 229-231 |
| Wed, 11/17 | Message passing, pp. 241-246 |
| Mon, 11/22 | Communicating over constrained noiseless channels, pp. 248-257 |
| Wed, 11/24 | Thanksgiving break (no class) |
| Mon, 11/29 | Crosswords and simple language models, pp. 260-264 |
| Wed, 12/1 | Model Comparison and Occam’s Razor (tentative) |
| Sat, 12/4 | (Final exam slot, part 1) Capacity of a Single Neuron (tentative) |
| Sat, 12/4 | (Final exam slot, part 1) TBD |

## Grading, attendance, and late work policy

There are 28 class sessions (including the final exam slot) where students will be presenting.
Students will be divided into four groups and students within a given group will rotate through the roles.
Each student will therefore present (or otherwise complete the requirement of one of the roles) 7 times.
Students will be assigned a grade out of 10 points for each presentation for a total of 70 points from presentations.
For each class session, students will also be given 1 point for attending the class, participating, and completeing assignments for non-presenting students (e.g. the Examiner).
The remaining 2 points are free!

Note that if you fall behind on the material, it will be increasingly hard for you to take on one of the roles that you will rotate through.
It's therefore crucial that you plan to attend all classes and stay on top of the readings (and, more than likely, read ahead in order to prepare the assignment for one of the roles).
If, for any reason, you need to miss a class where you'd be presenting, or fall behind on readings for any other reason, you'll need to let me know as early as possible so that we can plan accordingly.

All students are expected to follow the guidelines of the [UNC honor code](http://honor.unc.edu).
In the context of this class, it is particularly important that you cite the source of different ideas, facts, or methods and do not claim someone else's work as your own.
If you are unsure about which actions violate that honor code, feel free to ask me.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

Acts of discrimination, harassment, interpersonal (relationship) violence, sexual violence, sexual exploitation, stalking, and related retaliation are prohibited at UNC-Chapel Hill.
If you have experienced these types of conduct, you are encouraged to report the incident and seek resources on campus or in the community.
Please contact the Director of Title IX Compliance/Title IX Coordinator (Adrienne Allison, adrienne.allison@unc.edu), Report and Response Coordinators (Ew Quimbaya-Winship, eqw@unc.edu; Rebecca Gibson, rmgibson@unc.edu; Kathryn Winn kmwinn@unc.edu), Counseling and Psychological Services (CAPs) (confidential) in Campus Health Services at (919) 966-3658, or the Gender Violence Services Coordinators (confidential) (Cassidy Johnson, cassidyjohnson@unc.edu; Holly Lovern, holly.lovern@unc.edu) to discuss your specific needs.
Additional resources are available at http://safe.unc.edu.

## Resources

The University of North Carolina at Chapel Hill facilitates the implementation of reasonable accommodations, including resources and services, for students with disabilities, chronic medical conditions, a temporary disability or pregnancy complications resulting in difficulties with accessing learning opportunities.
All accommodations are coordinated through the Accessibility Resources and Service Office. See the ARS Website for contact information: https://ars.unc.edu or email ars@unc.edu.
Relevant policy documents as they relate to registration and accommodations determinations and the student registration form are available on the ARS website under the About ARS tab.

CAPS is strongly committed to addressing the mental health needs of a diverse student body through timely access to consultation and connection to clinically appropriate services, whether for short or long-term needs. Go to their [website](https://caps.unc.edu/) or visit their facilities on the third floor of the Campus Health Services building for a walk-in evaluation to learn more.

## Mask use

This semester, while we are in the midst of a global pandemic, all enrolled students are required to wear a mask covering your mouth and nose at all times in our classroom.
This requirement is to protect our educational community — your classmates and me – as we learn together.
If you choose not to wear a mask, or wear it improperly, I will ask you to leave immediately, and I will submit a report to the [Office of Student Conduct](https://cm.maxient.com/reportingform.php?UNCChapelHill&layout_id=23).
At that point you will be disenrolled from this course for the protection of our educational community.
Students who have an authorized accommodation from Accessibility Resources and Service have an exception.
For additional information, see [Carolina Together](https://carolinatogether.unc.edu/).

## Changes

I reserve the right to make changes to the syllabus, including project due dates and test dates.
These changes will be announced as early as possible.
