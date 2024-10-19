# Visualization Lab Project

Template repository for the Visualization lab project at the Johannes Kepler University Linz.

Please read through this `README.md` follow the instructions below.

For the detailed project specification check the [Visualization Moodel page](https://moodle.jku.at/course/view.php?id=31341).

## 0. Team Information

Fill out the `team-info.json` file in this repository and **push it to GitHub by 23:59 on 4 November, 2024**. (Check Moodle for any updated deadlines.)
Make sure that the file contains your team name, each student's first and last name, student ID, email address, and GitHub username.

## 1. Project Proposal

Fill out the `sub_01_proposal.ipynb` file and indicate the workloads for each student in the `sub_01_workload.json` file.

Make sure that the file includes your correct team name, that the names in the workload file match with the `team-info.json` and that the workloads sum up to 1.

**Push the files to GitHub by 23:59 on 11 November, 2024.**
(Check Moodle for any updated deadlines.)

## 2. Intermediate Project Submission

Fill out the `sub_02_intermediate.ipynb` file and indicate the workloads for each student in the `sub_02_workload.json` file.

Make sure that the file includes your correct team name, that the names in the workload file match with the `team-info.json` and that the workloads sum up to 1.

You can use the submission notebook for your experiments and to show your progress, but please keep a clear separation between any experimental outputs and the actual submission.

**Push the files to GitHub by 23:59 on 2 December, 2024.**
(Check Moodle for any updated deadlines.)

## 3. Final Project Submission

Fill out the `sub_03_final.ipynb` file and indicate the workloads for each student in the `sub_03_workload.json` file.

Make sure that the file includes your correct team name, that the names in the workload file match with the `team-info.json` and that the workloads sum up to 1.

You can use the submission notebook for your experiments and to show your progress, but please keep a clear separation between any experimental outputs and the actual submission.

**Push the files to GitHub by 23:59 on 16 January, 2025.**
(Check Moodle for any updated deadlines.)

## 4. Project Presentation

Add your slides and a video of your presentation to the `sub_04_presentation` folder. Please adhere to the following file extension and naming schemes: `presentation-video-<TEAMNAME>.mp4` and `presentation-slides-<TEAMNAME>.ppt(x)/pdf`. Please check Moodle for additional requirements such as the time limit.

Indicate the workloads for each student in the `sub_04_workload.json` file.
Make sure that the file includes your correct team name, that the names in the workload file match with the `team-info.json` and that the workloads sum up to 1.

**Push the files to GitHub by 23:59 on 16 January, 2025.**
(Check Moodle for any updated deadlines.)

## Communication

In case you have any questions about the individual submissions, please open a thread in the [Discussion Forum on Moodle](https://moodle.jku.at/mod/forum/view.php?id=10300502).
If you have issues with one of your teammates or do not agree about the workloads, please reach out to the course team via email.

## General Submission Information

* Make sure that you pushed your GitHub repository and not just committed it locally.
* **Make sure that the GitHub preview of your `.ipynb` files contains all parts of your submission that you want us to see!** In particular:
  * Check if all output for static visualizations is visible. If not, include a static screenshot as an image.
  * Check if all output for interactive visualizations is visible. If not, include a static screenshot and a link to a short screencast located in your repository.
* Feel free to use the provided `environment.yml` file as a starting point (instructions below). If you use additional libraries, keep the environment file up-to-date to keep your code easily executable for yourself and others.

## Usage Instructions

Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/vis-project-2024-<GROUP_NAME>.git
cd vis-project-2024-<GROUP_NAME>
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate vis-project
```

You might have to install the Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should now open a new tab with url http://localhost:8888/ and display the project files.



