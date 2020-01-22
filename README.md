# hackaton22Jan


# Goal of the hackaton
Goal of this hackaton is to create a NER algo able to recognize aircraft occurences in a document.

For instance:

"A Captain and First Officer of a <b>CE-560XL</b> reported..."

The main challenge is that there are no labels for the data. The onus is on you to create a dataset to train your algorithm. Your NER algo's performance will depend on the size of the supervized dataset you produce, as well as the learning strategy you choose.

# Expected result:
At the end of the day, the student will deliver a Flair SequenceTagger model that can be load through the following function: SequenceTagger.load('example_path/best_model.pt')

The model will then be evaluated on my own validation dataset and the results will be compared to determine the winner of the hackaton. The validation dataset is made up of sentences that can be found in the data that is provided.

# Data:
The data provided is the ASR dataset: "https://asrs.arc.nasa.gov".

You can access the data with the link provided below:

https://drive.google.com/open?id=1fqhnETNivqsV73cV-DPQXIqWFiO12mhw

Data is in pickle format, which can be used with pandas.read_pickle("path_to_pickle_file") function.

It is up to you to explore the data and decide on what to do with it in order to attain the expected results.

Good luck!
