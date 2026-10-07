# jn-Robo-Education-Recruitment
repository for member recruiting questions



## 1. What Git or GitHub features did you use in this task?
I mainly used git clone to clone the repository to my local machine, and I created a new repository on GitHub to store the files related to the recruitment task. In addition, after modifying files locally, I used git add and git commit to record the changes, and git push to sync my local commits to the GitHub repository. I also used the GitHub repository page to check files, commit history, and version changes.

## 2. What problems did you encounter during the process, and how did you solve them?
The main problems I encountered were:

1、Remote repository authentication failure: When pushing, I was told that I did not have permission or needed to log in. To solve this, I checked the remote repository URL and switched to HTTPS with a Personal Access Token.

2、I was not sure which directory a file should be placed in: I first read the repository's README.md and existing directory structure, then stored files according to the task requirements or templates to avoid creating a messy directory structure.

3、File conflicts: I opened the conflicting file, kept the correct content, removed the conflict markers, and then ran git add, git commit, and git push again.

## 3. If multiple Teaching Department members need to maintain this repository together in the future, how do you think files and the modification process should be organized?
I suggest organizing it from three aspects: directory standards, branch management, and review process.

File organization:

- Keep a README.md in the root directory explaining the repository's purpose, directory structure, usage, and maintenance rules.

- Divide directories by type, for example:

    - `/lesson-plans`: lesson plans

    - `/slides`: lecture slides

    - `/materials`: handouts, exercises, cases

    - `/assets`: images, templates, and other resources

    - `/archive`: past or expired materials

- Use consistent file naming, for example: 2025-spring-course-name-topic-v1, to avoid duplicate names and version confusion.

- Add a CONTRIBUTING.md that specifies commit rules, naming rules, and review requirements.

- Large files should not be placed directly in Git. Git LFS or cloud storage links can be used instead.

Modification process:

- Members should first run git pull to update the main branch.

- Each person should create their own branch, such as feature/xxx or fix/xxx, instead of modifying main directly.

- After making changes, commit them and push them to the remote branch.

- Open a Pull Request on GitHub explaining what was changed and why.

- At least one Teaching Department lead or relevant member should review it before merging into main.

- Regularly clean up merged branches, and tag or release important versions for archiving.

- Use Issues or a Projects board to assign tasks and avoid conflicts caused by multiple people modifying the same file at the same time.

## 4. Did you use AI tools in this recruitment assignment? If so, please explain which parts AI participated in and what checks and modifications you made.
I used AI tools to assist with part of the content. AI mainly participated in the initial production of the lesson plan and lecture slides, including organizing the teaching outline, generating a content framework, polishing wording, designing the slide structure, and supplementing example activities.

During the process, I made the following checks and modifications:

- Checked whether the lesson plan was complete according to the task requirements, including teaching objectives, class schedule, key and difficult points, and assessment methods.

- Combined it with my own professional background, adjusted cases, terminology, and knowledge points, and deleted inaccurate or unsuitable content.

- Checked whether the slide logic was coherent and avoided directly copying AI-generated content.

- Verified factual information, professional concepts, and cited sources to ensure there were no obvious errors.

- Unified the format, heading levels, and language style so that the final submission met the requirements of the recruitment assignment.

The final submitted content was screened, modified, and confirmed by me. AI was used only as an auxiliary tool.
