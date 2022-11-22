# Topic: Hash functions and Digital Signatures.

### Course: Cryptography & Security
### Author: Vasile Drumea

----

## Overview
&ensp;&ensp;&ensp; Hashing is a technique used to compute a new representation of an existing value, message or any piece of text. The new representation is also commonly called a digest of the initial text, and it is a one way function meaning that it should be impossible to retrieve the initial content from the digest.

&ensp;&ensp;&ensp; Such a technique has the following usages:
  * Offering confidentiality when storing passwords,
  * Checking for integrity for some downloaded files or content,
  * Creation of digital signatures, which provides integrity and non-repudiation.

&ensp;&ensp;&ensp; In order to create digital signatures, the initial message or text needs to be hashed to get the digest. After that, the digest is to be encrypted using a public key encryption cipher. Having this, the obtained digital signature can be decrypted with the public key and the hash can be compared with an additional hash computed from the received message to check the integrity of it.


## Examples
1. Argon2
2. BCrypt
3. MD5 (Deprecated due to collisions)
4. RipeMD
5. SHA256 (And other variations of SHA)
6. Whirlpool


## Objectives:
1. Get familiar with the hashing techniques/algorithms.
2. Use an appropriate hashing algorithms to store passwords in a local DB.
    1. You can use already implemented algortihms from libraries provided for your language.
    2. The DB choise is up to you, but it can be something simple, like an in memory one.
3. Use an asymmetric cipher to implement a digital signature process for a user message.
    1. Take the user input message.
    2. Preprocess the message, if needed.
    3. Get a digest of it via hashing.
    4. Encrypt it with the chosen cipher.
    5. Perform a digital signature check by comparing the hash of the message with the decrypted one.

   
## Implementation tips:

1. Keep in mind, program to interfaces not implementations. In other words, use abstractions as much as possible to make your project more open for extension and closed for modification.

2. Please use packages/directories to logically split the files that you will have. It would be really great to get rid of the lab#X folders from your projects.

3. The new .md file (i.e. the fourth report) should be at the same level as the first one.


## Evaluation:
1. The project should be located in a public repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository,
  * You can structure the works in separate directories, but the separation should be logical based on the types of the files.
  * The reports should be put in a separate folder.

2. It should contain an explanation in the form of a Markdown with the standard structure from the REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The lab works can be presented by you as well if you want.

4. You need to submit on ELSE the URL to the repository.

5. If the work doesn't correspond to the requirements I grade it with an insufficient mark and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __20/11/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.

9. Also, I'll start penalizing for not fixing previous works as indicated in the received evaluation feedback, if any.
