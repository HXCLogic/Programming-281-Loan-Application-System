# Programming-281-Loan-Application-System
This project, the Loan Application System, is designed to facilitate the management of construction loans offered by Unique Building Services Loan Company. The system categorizes loans into business and individual loans, with a maximum loan amount of R100,000. The application is implemented in C# as a Console application.

**Milestone 1:**

This milestone constitutes the core functionality of the Loan Application System. It involves the implementation of various classes and interfaces to manage loans effectively.

* **Loan Class**: An abstract class representing a loan, implementing the LoanConstants interface. The Loan class encapsulates essential loan data such as loan number, customer name, loan amount, interest rate, and term. The constructor ensures data integrity by enforcing a maximum loan amount of R100,000 and defaults the loan term to a short-term if not explicitly defined.
* **LoanConstants Interface**: A public interface defining constant values for loan terms (short, medium, long) and other relevant constants such as company name and maximum loan amount.
* **BusinessLoan Class**: A subclass of Loan, tailored for business loans. It sets the interest rate to 1% more than the current prime interest rate.
* **PersonalLoan Class**: A subclass of Loan, designed for individual loans. It sets the interest rate to 2% more than the current prime interest rate.
* **CreateLoans Application**: This application facilitates the creation of loan objects by prompting the user for relevant information such as loan type and associated data. It then stores the created loan objects in an array and displays them upon completion.

**Milestone 2:**

In this milestone, the focus shifts towards creating a user manual to aid users in utilizing the Loan Application System effectively.

* **User Manual**: A concise user manual comprising appropriate screenshots and instructions for using the system. The manual is designed to be user-friendly and informative, providing users with a clear understanding of the system's functionalities. It is limited to a maximum of 6 pages and includes a dynamic table of contents for easy navigation.

**Submission Guidelines:**

* The project must be developed using Visual Studio 2019/2022.
* Submit a zipped file containing the codebase along with the user manual.
* Ensure adherence to submission instructions to avoid forfeiture of marks.

**Additional Notes**:

* Collaboration is encouraged, with projects to be completed in groups of 4 or 5 students.
* Stay updated with any additional instructions provided by the lecturer via Microsoft Teams.
* Preparedness for presenting the project in class on the submission date is essential for evaluation.
  
This project constitutes a significant assessment in Programming 2781, with a total of 50 marks allocated across Milestones 1 and 2.
