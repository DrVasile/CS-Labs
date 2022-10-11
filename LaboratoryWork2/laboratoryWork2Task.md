# Topic: Symmetric Ciphers. Stream Ciphers. Block Ciphers.

### Course: Cryptography & Security
### Author: Vasile Drumea

----

## Overview
&ensp;&ensp;&ensp; Symmetric Cryptography deals with the encryption of plain text when having only one encryption key which needs to remain private. Based on the way the plain text is processed/encrypted there are 2 types of ciphers:
- Stream ciphers:
    - The encryption is done one byte at a time.
    - Stream ciphers use confusion to hide the plain text.
    - Make use of substitution techniques to modify the plain text.
    - The implementation is fairly complex.
    - The execution is fast.
- Block ciphers:
    - The encryption is done one block of plain text at a time.
    - Block ciphers use confusion and diffusion to hide the plain text.
    - Make use of transposition techniques to modify the plain text.
    - The implementation is simpler relative to the stream ciphers.
    - The execution is slow compared to the stream ciphers.

&ensp;&ensp;&ensp; Some examples of stream ciphers are the following:
- Grain: ...
- HC-256: ...
- PANAMA: ...
- Rabbit: ...
- Rivest Cipher (RC4): It uses 64 or 128-bit long keys. It is used in TLS/SSL and IEEE 802.11 WLAN.
- Salsa20: ...
- Software-optimized Encryption Algorithm (SEAL): ...
- Scream: ...

&ensp;&ensp;&ensp; The block ciphers may differ in the block size which is a parameter that might be implementation specific. Here are some examples of such ciphers:
- 3DES
- Advanced Encryption Standard (AES): A cipher with 128-bit block length which uses 128, 192 or 256-bit symmetric key.
- Blowfish: ...
- Data Encryption Standard (DES): A 56-bit symmetric key cipher.
- Serpent: ...
- Twofish: A standard that uses Feistel networks. It uses blocks of 128 bits with key sizes from 128-bit to 256-bit.


## Objectives:
1. Get familiar with the symmetric cryptography, stream and block ciphers.

2. Implement an example of a stream cipher.

3. Implement an example of a block cipher.

4. The implementation should, ideally follow the abstraction/contract/interface used in the previous laboratory work.

5. Please use packages/directories to logically split the files that you will have.

6. As in the previous task, please use a client class or test classes to showcase the execution of your programs.

   
## Implementation tips:

1. In order to make the most out of OOP principles and make your project more flexible to changes you need to think in advance about the following things:
    - What pieces of implementation could be shared in multiple classes. If you have such things maybe those could be raised on one level of abstraction higher (i.e. in a parent class).
    - Program using abstractions when possible. If you can abstract things away by using a parent class instead of the child ones do that, because it makes the implementation more flexible in case the child classes need to be changed.
    - Follow SOLID Principles. If needed we can discuss these at lectures.
2. The second laboratory work should be a part of the same repository and maybe even of the same module. The new .md file (i.e. the second report) should be at the same level as the first one. You can put the reports in a separate folder. In general, try to make the placement of files as coherent as possible. If a folder contains a lot of different files, probably that's not very coherent and could be structured in sub directories. 


## Evaluation:
1. The project should be located in a public repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository.
  * You can structure the works in separare directories.
  * For now there is no need to use libs/frameworks.

2. It should contain an explanation in the form of a Markdown with the standard structure from the REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The works can be presented by you as well if you want.

4. You need to submit on ELSE the URL to the repository. (__NOTE__: Be aware that sometimes on ELSE you need to submit the assignment after it is in draft state. So if it is in draft it will not be evaluated).

5. If the work doesn't correspond to the requirements I'll revert the submission and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __12/10/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.

