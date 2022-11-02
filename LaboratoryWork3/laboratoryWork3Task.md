# Topic: Asymmetric Ciphers.

### Course: Cryptography & Security
### Author: Vasile Drumea

----

## Overview
&ensp;&ensp;&ensp; Asymmetric Cryptography (a.k.a. Public-Key Cryptography)deals with the encryption of plain text when having 2 keys, one being public and the other one private. The keys form a pair and despite being different they are related.

&ensp;&ensp;&ensp; As the name implies, the public key is available to the public but the private one is available only to the authenticated recipients. 

&ensp;&ensp;&ensp; A popular use case of the asymmetric encryption is in SSL/TLS certificates along side symmetric encryption mechanisms. It is necessary to use both types of encryption because asymmetric ciphers are computationally expensive, so these are usually used for the communication initiation and key exchange, or sometimes called handshake. The messages after that are encrypted with symmetric ciphers.


## Examples
1. RSA
2. Diffie-Helman
3. ECC
4. El Gamal
5. DSA


## Objectives:
1. Get familiar with the asymmetric cryptography mechanisms.

2. Implement an example of an asymmetric cipher.

3. As in the previous task, please use a client class or test classes to showcase the execution of your programs.

   
## Implementation tips:

1. Keep in mind, program to interfaces not implementations. In other words, use abstractions as much as possible to make your project more open for extension and closed for modification.

2. Please use packages/directories to logically split the files that you will have. If you need a good quick read from which to learn project design practices search for "Design Principles and Design Patterns" by Robert C. Martin.

3. Once again, the third laboratory work should be a part of the same repository and maybe even of the same module. The new .md file (i.e. the third report) should be at the same level as the first one. You can put the reports in a separate folder.


## Evaluation:
1. The project should be located in a public repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository.
  * You can structure the works in separare directories.
  * For now there is no need to use libs/frameworks.

2. It should contain an explanation in the form of a Markdown with the standard structure from the REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The works can be presented by you as well if you want.

4. You need to submit on ELSE the URL to the repository. (__NOTE__: Be aware that sometimes on ELSE you need to submit the assignment after it is in draft state. So if it is in draft it will not be evaluated).

5. If the work doesn't correspond to the requirements I'll revert the submission and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __26/10/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.