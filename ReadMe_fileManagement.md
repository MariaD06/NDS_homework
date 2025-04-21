
For the all the coding labs, we will use a single repository, with the following folder structure.

NDS_homework
├── notebooks
│   └── AI_CodingLab1.ipynb
│   └── MD_CodingLab1.ipynb
│   └── AI_CodingLab2.ipynb
│   └── MD_CodingLab2.ipynb
│   └── ...
├── matplotlib_style.txt
└── requirements.txt


Given that Git becomes very slow with many data files, I suggest we keep the data in a different folder, and only do version control with `NDS_homework`.

NDS_data
│   └── nds_cl_1.csv
│   └── nds_cl_2.csv
│   └── ...


My suggestion:
- When each homework is released, I will add the data and template `.ipynb` file to our folder structure. Then everybody syncs with the repo, and then forks a copy of the repository, and works on a separate branch. During our Tuesday/Wednesday meeting, we discuss our code and then merge the different branches.

- When merging the branches, we will need to have the same filename (e.g. `CodingLab1.ipynb`). But when working independently, maybe it's best if we add our initials to `_CodingLab1.ipynb` before working with them. This makes sure that if we do a mistake during merging, we still have our individual codes in a separate files. During our meting, we can e.g. just copy `AI_CodingLab1.ipynb`, remove initials and then merge.


Helpful resources:
- https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo


