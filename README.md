# MultimediaRetrieval_2021

Project developed for the course "Multimedia Retrieval". The aim is to build an end-to-end pipeline that is able to retireve similar 3D shapes to a given user input shape, from a database of 3D shapes. The project deals with several challanges: set up a 3D shapes viewer, re-mesh all the shapes in the database, perform 4 normalisation steps on all the shapes (translation to (0, 0, 0), alignment of eigenvectors, flipping and scaling), extract their features and standardise them. Then, create a similarity function to compare feature vectors of different shapes. After this, tackle the scalability issues, provide a dimensionality reduction graph and evaluate the whole pipeline.

In this repository are contained the code of the application (with the instructions to set it up) and the report describing in detail each step.

Course website: https://webspace.science.uu.nl/~telea001/MR/MR

Assignment explanation: https://webspace.science.uu.nl/~telea001/MR/Assignment
