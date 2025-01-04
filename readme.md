We have run everything on Google Colab, the libraries needed are in requirements.txt
Aside from original libraries that are already installed in Colab, we installed just one more library:
adversarial-robustness-toolbox with
!pip install adversarial-robustness-toolbox
(you can see that cell in every notebook at the start of the notebook)

To successfully run the notebooks, make a folder 'MLEX3' in Google Drive and then put the everything
from this zipped folder into that 'MLEX3' folder

structure would look like this:
\MyDrive (base directory in Google Drive)
-\MLEX3
--\data
--adversarial_training.ipynb
--attacks_only.ipynb
--distillation.ipynb


