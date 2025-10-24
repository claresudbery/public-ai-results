Creating Kit Links Process

STARTER_CHARACTER = 🔗

Create a Kit post url from the title the user gives you.
Start by asking the user for the title, then turn that title into a url.
The url will be prefixed with `https://queen-of-questions.kit.com/posts/`, and will be followed by all the text from the title, but the title text will be altered in the following ways:
- All punctuation will be removed
- Apostrophes will be replaced by hyphens
- All letters will be lower case
- All words will be separated by hyphens
Here is an example: The post is titled "I'm a tech lead, but my senior devs have better technical skills. Am I losing my edge?", and the resulting url is `https://queen-of-questions.kit.com/posts/i-m-a-tech-lead-but-my-senior-devs-have-better-technical-skills-am-i-losing-my-edge`