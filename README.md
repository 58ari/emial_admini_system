<h1>Company Email Account Generator</h1>

**Overview**

The Company Email Account Generator is a Java project that exemplifies the implementation of Object-Oriented Programming (OOP) concepts in a practical setting. This project aims to automate the process of generating email accounts for newly hired employees in a company.

**Features**

    ● Automated creation of email accounts for new employees.
    
    ● Default password assignment for the newly created email accounts.
    
    ● Flexibility to change passwords, set alternate email addresses, and define mailbox capacities.
    
    ● Generation of random email addresses following the format
    
      'firstName.lastName@department.company.com'.
    
    ● Integration of a company-specific email address format.
    
    ● Basic validation to ensure the provided department is valid.

  
 **Installation**
 
   1. Clone the repository:

          git clone https://github.com/your-username/company-email-account-generator.git

   2. Open the project in your preferred Java Integrated Development Environment (IDE).

   3. Build the project to resolve dependencies and compile the source code.


**Usage**

  1.Import the necessary classes and packages:

    import com.company.EmailAccount;
    import com.company.Department;
    // ...

  2. Instantiate the EmailAccount class:

    EmailAccount emailAccount = new EmailAccount("John", "Doe", Department.DEVELOPMENT);

  3. Generate the email account:

    emailAccount.generateEmail();

  4. Access the generated email account details:

    String email = emailAccount.getEmail();
    String password = emailAccount.getPassword();
    // ...

  5. Customize the email account:

    emailAccount.changePassword("newPassword");
    emailAccount.setAlternateEmail("johndoe@gmail.com");
    // ...

