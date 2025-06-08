# resume
- A little repo to store my resume
- Heavily inspired by this [blog post](https://aless.co/resume-as-code) and this [github repo](https://github.com/dcousineau/resume)!

## How to make changes so a pdf is generated
1. Make your changes to resume.tex
2. commit changes
3. Run 'git tag <tag_name> HEAD' to tag your last commit
    - Follow the convention v*.*
    - run 'git tag' to see already created tags
4. Run 'git push --follow-tags' to push changes with your newly created tag