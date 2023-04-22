# datasciencecoursera
Data Science Course Project Stephan

Checking If it updates

Problems encountered during the Coursera assignment:

-The course is not up to date. It lacks very specific details and information that was added in updates to Github. More specifically when having to set up your account and email from Github into Git Bash.

The course didnt mentioned that you must check if your email is privated on your Github settings or not. When making your new account your email will be private, meaning that any pull and push actions made using your regular email will not happen.

Instead if your email is privated you must use instead as an email [ID]+[UserName]@users.noreply.github.com where your ID and Username can be found on your Github Settings on the Emails tap.

-There is no problem when openning a RStudio Project that is local. But when trying to open a RStudio that is linked to a reppo in Github the app will try to open the project multiple times, openning multiple RStudio over and over again, creating multiple processes to the point that it makes you think RStudio decided to become malware.

The only way to stop it I found was to open taskmanaged and keep closing any new RStudio process until the original or one of the new ones manages to open the project. At that point once loaded RStudio will stop launching new windows/processes.