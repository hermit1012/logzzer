# logzzer
Java fuzzer for Log4Shell.

On December 9th, 2021, the Remote Code Execution (RCE) CVE-2021-44228 in Apache log4j 2 was published and started seeing active exploitation soon after.  Since then, development teams have been working hard and tirelessly, trying to fix the issue to prevent (further) damage.

Logzzer is a fuzzer that biases coverage-guided fuzzing towards producing semantically valid inputs for Java application. The inputs it generates is designed according to the characteristics of this Log4Shell. 
