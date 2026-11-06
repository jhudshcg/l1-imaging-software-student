# Imaging Software — student resources

Open [the Photoshop skills guide](guides/guide-imaging-software.html) in your web browser. If you see code on GitHub, download the resource pack and open the HTML file from the downloaded folder.

Keep the folders together so links and pictures work. Save your own work in your college OneDrive Imaging Software folder. No Git or code editor is needed.

- [Starter brief and setup card](templates/kickstart-starter-brief.html)
- [Annotated layout example](examples/poster-layout-example.html)
- [Practice camera](assets/practice-camera.png) and [background](assets/practice-background.png)
- [Practice image source notes](assets/source-notes.txt)

Use the assessment booklet supplied by your teacher. Guide steps match its task numbers. This pack is a draft: your teacher confirms the course facts, contact route and hand-in location.

## Teacher / repository handoff

The unit specification and assessment booklet sources live in the parent course repository, outside this student pack. The booklet is generated with the shared Pandoc template and Lua filter.

Repository: [jhudshcg/l1-imaging-software-student](https://github.com/jhudshcg/l1-imaging-software-student), public to match the existing student repositories, with topic `level-1`. The remote is empty until the first teacher commit is pushed. Local `origin` and the parent `.gitmodules` entry are prepared; no gitlink can be recorded until that first commit exists.

No commits are made by the drafting agent. A real submodule requires a commit in this repository before the parent can record its revision. After reviewing these files, create the first commit and push it from this repository. Then, from the parent repository, stage `.gitmodules` and `Imaging Software/l1-imaging-software-student`; Git records the student repository's committed revision as a gitlink. After staging the submodule, `git submodule absorbgitdirs` can move its Git metadata into the parent’s standard submodule storage. Review the parent change before committing it yourself. Changes inside the student repository must be committed there before a new revision can be recorded by the parent.

The HTML pages use local images and styles; no remote scripts, fonts or accounts are required. External help links need internet access. The example is a layout study, not a layered PSD or a completed assessed project.
