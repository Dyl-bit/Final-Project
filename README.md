# Final-Project

## Motivation

I made this project because I wanted to create something that's both useful and simple to run on any basic Java compiler. 

## How to run the code

First, for the code to work, you need to download both JavaMail API and JAF from the official Java website. Then you extract them, and add mail.jar, smtp.jar, and activation.jar in your classpath for it to be eligable to send emails, though in this case I edited it enough for those things to not be neccessary. 

## Code Example

 Message message = new Message(session);

        message.setFrom(new InternetAddress(sender));

        message.equals();


        message.setSubject("This is Subject");


        message.setContent("<h1>This is a HTML text</h1>","text/html");


        Transport.send(message);
        System.out.println("Mail successfully sent");
    }

    private static class TO {
    }
}

I am proud of this segment of code because I was able to edit and simplify it enough after fixing many different errors in the code. 

### Tests

After the email and message information you input in the code is complete, simply press the run button and it should display a message that the email was successfully sent. 

[Project Code.txt](https://github.com/Dyl-bit/Final-Project/files/11298121/Project.Code.txt)


### Contributors

This project's contributors are my professor, Jason Adams. If any part of the code appears to not be in order, contributors can observe it in this file: 
[FinalProject.zip](https://github.com/Dyl-bit/Final-Project/files/11298104/FinalProject.zip)
