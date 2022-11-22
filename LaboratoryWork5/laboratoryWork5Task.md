# Topic: Web Authentication & Authorisation.

### Course: Cryptography & Security
### Author: Vasile Drumea

----

## Overview

&ensp;&ensp;&ensp; Authentication & authorization are 2 of the main security goals of IT systems and should not be used interchangibly. Simply put, during authentication the system verifies the identity of a user or service, and during authorization the system checks the access rights, optionally based on a given user role.

&ensp;&ensp;&ensp; There are multiple types of authentication based on the implementation mechanism or the data provided by the user. Some usual ones would be the following:
- Based on credentials (Username/Password);
- Multi-Factor Authentication (2FA, MFA);
- Based on digital certificates;
- Based on biometrics;
- Based on tokens.

&ensp;&ensp;&ensp; Regarding authorization, the most popular mechanisms are the following:
- Role Based Access Control (RBAC): Base on the role of a user;
- Attribute Based Access Control (ABAC): Based on a characteristic/attribute of a user.


## Objectives:
1. Take what you have at the moment from previous laboratory works and put it in a web service / serveral web services.
2. Your services should have implemented basic authentication and MFA (the authentication factors of your choice).
3. Your web app needs to simulate user authorization and the way you authorise user is also a choice that needs to be done by you.
4. As services that your application could provide, you could use the classical ciphers. Basically the user would like to get access and use the classical ciphers, but they need to authenticate and be authorized. 

## Implementation tips:

1. First, there is not need for front-end. You can use Postman, or other client apps to make requests to your services, create/ammend users etc. Also, you can have pre-created users in a local database and use them to show-case the functioning of your web services.

2. You'll probably have to do refactoring of what you already have, which is a good thing, and if the suggestions from previous works were used it whouldn't be hard.

3. You can use web frameworks or any libraries as needed.

## Evaluation:
1. The project should be located in a public repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository,
  * You can structure the works in separate directories, but the separation should be logical based on the types of the files.
  * The reports should be put in a separate folder.

2. It should contain an explanation in the form of a Markdown with the standard structure from the REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The lab works can be presented by you as well if you want.

4. You need to submit on ELSE the URL to the repository.

5. If the work doesn't correspond to the requirements I grade it with an insufficient mark and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __15/12/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.

9. Also, I'll start penalizing for not fixing previous works as indicated in the received evaluation feedback, if any.