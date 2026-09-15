This Project is made to solve the trouble that involved with ICA and CSP algorithm.

[Explain the situation]
    I was doing tutorial for Motor Imgaery Classification using 'MNE library'.
    I used 'BCI Competition IV 2a' dataset.
    The problem was the result of ICA algorithm.
    It was different from what I expected.
    I expected that C3, C4 areas will appear. Because this MI mission includes 'left/right events' and these events affect C3, C4 areas.
    But there is no such thing.
    SO denosing was not going well. And as a domino effect, CSP also didn't work well.


[dataset]
    I used 'BCI Competition IV 2a' dataset.
    this is for Motion Imagery task.
    details in 'desc_2a.pdf' in 'dataset' folder.


[directory description]
root
|
|--dataset : Use this dataset in this repo.
|
|--notebooks : ipynb files
|     |--original.ipynb : the file that first trouble arised. It is not updated.
|     |--test.ipynb : the file that many tests are tried to solve the trouble. 
|     |--updated.ipynb : the file that will be updated the solutions in test.ipynb.
|
|--venv : virtual environment
|
|--README.md
|
|--.gitignore