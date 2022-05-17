# Streamline SSH Configuration
I had to create a config file for the login to continue withe the configuration.
![](Editsshconfig.png)
Afterthat, I went onto log onto the remote server using the code `ssh ieng6`.
![](LoginWithConfig.png)
With the new login, I was allowed to use commands without typing all of the User info, and here is an example:
![](CopyInConfig.png)
---
# Setup Github Access from ieng6
I first started off by copying my key to Github, and here is a screenshot of the copy:
![](GithubKey.png)
Here is also a picture of where the private key is held:
![](PrivateKey.png)
After these preparations, I was able to commit from the config rather than from GitHub desktop, as shown here:
![](GitHubCommitInConfig.png)
I know this commit went through because of the commit history shown here [history](https://github.com/nidhidhamnani/markdown-parser/compare/main...jrbryant55:main)
---
# Copy whole directories with scp -r
First, I just used the command `scp -r cs15lsp22ady@ieng6.edu:~/markdown-parser` to copy the directory.
![](scp-r1.png)
![](scp-r2.png)
After copying, I was able to run JUnit tests with the javac, java commands
![](JUnitTest.png)
I was able to run both tests by combining `scp` and `ssh`.
![](JUnitTest2.png)