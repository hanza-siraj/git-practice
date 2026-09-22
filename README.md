# Git Practice
A simple project to practice a few git/github workflows.  Replace the contents of this file with the contents indicated in the [instructions](./instructions.md).

## Why Less Is Not Always More in AI-Assisted Coding

[How we make AI coding more cost efficient without sacrificing task quality](https://github.blog/ai-and-ml/github-copilot/how-we-make-ai-coding-more-cost-efficient-without-sacrificing-task-quality/)

What I found interesting is the article's argument that making every individual AI response shorter does not necessarily make the whole coding process more efficient. A response can save tokens but leave out useful context, forcing the system to make more calls and take longer to finish the task. GitHub's team instead measured efficiency across the full workflow and tested changes such as removing repetitive output while preserving information the coding agent would need later.

That idea connects to a broader problem in software engineering: optimizing one easy-to-measure number can make the overall system worse. I have seen a similar tension in machine learning work, where improving a single metric does not always mean the model is more useful in practice. The article was a good reminder that engineering decisions should be judged by the final outcome, not just by a convenient local metric like token count, response length, or even lines of code.