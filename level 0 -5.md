## visit - http://natasX.natas.labs.overthewire.org.

> level 0 -> just visit  http://natas0.natas.labs.overthewire.org and enter 'natas0 as username and password both.<br>
> level 1 -> <img width="388" alt="image" src="https://user-images.githubusercontent.com/88367072/230738848-2234ffe4-1b69-4ba2-b789-5da6a1396a29.png">

  <br>use page source settings
  <img width="550" alt="image" src="https://user-images.githubusercontent.com/88367072/230738765-da4322fa-db20-46a9-9018-5fe11afc0147.png">

  
> level 2 -> use the shortcut key to enter into  'page source on your browser'  <img width="494" alt="image" src="https://user-images.githubusercontent.com/88367072/230738818-e8e726e7-69de-40f5-bed4-9e03a76ef50c.png">

<img width="461" alt="image" src="https://user-images.githubusercontent.com/88367072/230738869-aee44c22-6b66-4b5a-8077-67de7c01f423.png">


> level 3 -> its written "there is nothing on this page-
- step1 ) use page source 
- step2) get to the link (img) and get to the file directory .
- step3) on this webpage - we will see a user.txt file here our password is stored.
<img width="319" alt="image" src="https://user-images.githubusercontent.com/88367072/230739161-4957b181-8c9d-4aaa-8329-d0b8e3442d66.png">

> level 4 -
 Robots.txt is a file that webmasters create to instruct web robots, also known as web crawlers or spiders, how to interact with their website. It is a plain text file that is placed in the root directory of a website and is named "robots.txt".

The robots.txt file contains instructions that tell web robots which pages or sections of a website they are allowed to access and which pages they should not access. For example, it can be used to block search engine crawlers from indexing certain pages, directories, or files on the website.

- step1) get to the robots.txt webpage
- step2) the robots.txt page give the link of a directory /s3cr3t/
- step3) access this directory and u will find the password  'tKOcJIbzM4lTs8hbCmzn5Zr4434fGZQm '

> level 5 -
using burpsuite to change the info of the Referer.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/88367072/230740882-d5cc7f39-2c69-4cd5-beb5-a03230db34ff.png">

flag - 
