**We are not taking non-UW interns right now. We will update this page if the circumstance changes.**

# CompLING Lab Internship Practice
This repository contains a set of tasks to help you practice your coding skills.
Each task is designed to help you get started with one specific research project with [Freda](https://cs.uwaterloo.ca/~fhs/) and the CompLING Lab.
Your work on the task will be part of your application.
Your application will be evaluated based on the quality of your code and the clarity of your report.

**Note to UW Co-Op Applicants**:
Please apply for URA first and work with us for at least three months. Freda will be happy to take outstanding URAs from the group as co-op students.

**Note to Non-UW Students**:
You are welcome to complete these tasks.
Although Freda is not looking for onsite visiting students or interns before Fall 2024, she will have openings starting Fall 2024 through the [Vector Internship Program](https://vectorinstitute.ai/programs/internships/), the [Mitacs Globalink Program](https://www.mitacs.ca/our-programs/globalink-research-internship-students/), or direct admissions.

## How to Complete and Submit Your Work
1. Clone this repository and run the following command to install the required style-checking tools:
    ```bash
    pip install pre-commit
    pre-commit install
    ```

    At the CompLING Lab, we follow the [Google Python style guide](https://google.github.io/styleguide/pyguide.html) (excluding the 80-character-per-line rule; E501) to maintain the readability of code.
    We use `flake8-docstrings` (see more [here](https://pypi.org/project/flake8-docstrings/)) to check for format.
    Your code should be committable after installing the above tools; alternatively, you may run `flake8 FILE_NAME` to check the style of a specific file.

2. Choose **one** task from the [available ones](#currently-available-tasks) and complete it following the guidelines.
Feel free to skip the background section if you are already familiar with the content, but please make sure to read all instructions carefully and follow them strictly. \
If you have questions, please open an issue in this repository.
Freda and the CompLING Lab members will respond as early as possible.
Due to the large volume, Freda can not respond to emails regarding practice problems or internship requests.

3. Submit your project report and code using [this form](https://forms.gle/HrCimoc2SRMBJzHF6). Freda and the CompLING Lab members will manage to respond within a week. Please email Freda **only if you have not received a response after a week.**

## Currently Available Tasks
1. Next Word Distribution: See task descriptions and instructions [here](tasks/01-next-word-distribution.pdf).
