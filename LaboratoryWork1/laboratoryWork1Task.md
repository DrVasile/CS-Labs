# Topic: Intro to Cryptography. Classical ciphers. Caesar cipher.

### Course: Cryptography & Security
### Author: Vasile Drumea

----

## Overview
&ensp;&ensp;&ensp; Cryptography consists a part of the science known as Cryptology. The other part is Cryptanalysis. There are a lot of different algorithms/mechanisms used in Cryptography, but in the scope of these laboratory works the students need to get familiar with some examples of each kind.

&ensp;&ensp;&ensp; First, it is important to understand the basics so for the first task students will need to implement a classical and relatively simple cipher. This would be the Caesar cipher which uses substitution to encrypt a message. 

&ensp;&ensp;&ensp; In it's simplest form, the cipher has a key which is used to substitute the characters with the next ones, by the order number in a pre-established alphabet. Mathematically it would be expressed as follows:

$em = enc_{k}(x) = x + k (mod \; n),$

$dm = dec_{k}(x) = x + k (mod \; n),$ 

where:
- em: the encrypted message,
- dm: the decrypted message (i.e. the original one),
- x: input,
- k: key,
- n: size of the alphabet.

&ensp;&ensp;&ensp; Judging by the encryption mechanism one can conclude that this cipher is pretty easy to break. In fact, a brute force attack would have __*O(nm)*__ complexity, where __*n*__ would be the size of the alphabet and __*m*__ the size of the message. This is why there were other variations of this cipher, which are supposed to make the cryptanalysis more complex.


## Objectives:
1. Get familiar with the basics of cryptography and classical ciphers.

2. Implement 4 types of the classical ciphers:
    - Caesar cipher with one key used for substitution (as explained above),
    - Caesar cipher with one key used for substitution, and a permutation of the alphabet,
    - Vigenere cipher,
    - Playfair cipher.
    - If you want you can implement other.

3. Structure the project in methods/classes/packages as neeeded.

   
## Implementation tips:

1. You can organize the implemented algorithms in separate classes.

```
public class CipherA
{
    // Some state variables if needed.

    private final String substitutionKey;
    private final String permutationKey;

    public CipherA(final String substitutionKey, final String permutationKey)
    {
        ...
    }

    public String encryptMessage(final String message)
    {
        // The implementation of Cipher A.
    }

    public String decryptMessage(final String encryptedMessage)
    {
        // The implementation of decryption of Cipher A.
    }

}
```

2. In order to show the execution you can implement a client class, which is just a "Main" class in which you can instantiate the cipher objects and use them to encrypt messages. Another approach would be to write unit tests for each cipher and that way to show their correctness.


## Evaluation:
1. The project should be located in a public repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository.
  * You can structure the works in separate directories.
  * For now there is no need to use libs/frameworks.

2. It should contain an explanation in the form of a Markdown with the standard structure from the REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The works can be presented by you as well if you want.

4. You need to submit on ELSE the URL to the repository. (__NOTE__: Be aware that sometimes on ELSE you need to submit the assignment after it is in draft state. So if it is in draft it will not be evaluated).

5. If the work doesn't correspond to the requirements I'll revert the submission and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __29/09/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.

