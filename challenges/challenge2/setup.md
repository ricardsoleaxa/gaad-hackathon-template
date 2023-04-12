# Workspace Configuration Instructions
## Challenge 2: Accessible Contracts

| Topic | Description |
| --- | --- | 
| Overview | The use of complex language in contracts and legal text makes them difficult to understand, particularly for individuals with cognitive disabilities. |
| Challenge | Organize a well-rounded team that will develop a generic solution to simplify the language used in contracts, improve their overall clarity and accessibility, and make them easier to find and understand. This solution should be flexible enough to be deployed in any infrastructure.|
## Event Track
Challenge 2 offers one event track.

| Track | Description | Key Submission Artifacts | Required Skills |
| --- | --- | --- | --- | 
| **Design Thinking / Hack the Code** | Develop a working end-to-end solution applying the Design Thinking methodology and using the AXA Computable Contracts API to deliver a more simplified version of a contract where  understandability and clause findability are enhanced. | Link to a Visual Collaboration Software Board (Mural), Use case story, Journey map, basic research and user testing results, Demo code, 2-min Concept Playback Pitch Video, 2-min Demo Video | Teams shoud ideally include mixed profiles. Usefull skills unclude: UX Research & Design, UX Writing, Developers |

## Update Readme
1. Open the locally cloned repository on your **Development Workstation** using your favorite IDE (i.e. [Visual Studio Code][1], [Atom][2]).
2. Based on track selected, copy the appropriate `sample code` to prime your project workspace within the `hackproject` folder.

    ```
    $ cd <REPO_FOLDER>
    $ cp -Rv ./common/* ./hackproject/
    $ cp -Rv ./challenges/challenge2/* ./hackproject/
    $ rm -f ./hackproject/setup.md
    $ rm -f ./hackproject/.gitkeep
    ```

    where:
    
    * REPO_FOLDER: Name of the local project folder on your **Development Workstation** after cloning the ``` Team Workspace``` repository.

3. Move `README.md` to the `archive` folder. Rename it to `ORIGINAL_INSTRUCTIONS.md`.

    ```
    $ mv -fv ./README.md ./archive/ORIGINAL_INSTRUCTIONS.md
    ```

4. Rename `SUBMISSION_README.md` to `README.md`

    ```
    $ mv -fv ./SUBMISSION_README.md ./README.md
    ```

5. Update new `README.md` according to the Template Instructions therein.

## Develop Solution
During the event publish all work to the Team Workspace. Follow these [submission instructions](../../submission-guides/submission-instructions.md) prior to finalizing the team's project submission.  

[1]: https://code.visualstudio.com/
[2]: https://atom.io
[3]: https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository
[4]: https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository
[5]: https://github.com/discoverfinancial/a11y-theme-builder
