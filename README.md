# Crypto-Answer

## Using our system: ##

1. Upload "training_data_fine_tuning.json" to [Google Drive](http://drive.google.com/). Make sure it is in the right folder. The folder structure is as following: "Colab Notebooks/Crypto-Answer/data/squad20/
2. Upload "crypto-answer-il2.ipynb" to [Google Colab](https://colab.research.google.com/). Make sure you have the runtime settings on "GPU"
3. Run all blocks of code in colab (with GPU enabled it will take ~ 25 min)
3.1 Connect colab to google drive with clicking on the link, displayed under the corresponding code block, copying the code into the input-field and finally pressing enter
3.2 If you do not have access to google drive, you can also upload "training_data_fine_tuning.json" directly to colab. In this case you haave to change data_dir variable to ""
4. Open our website under: "https://crypto-answer-il2.anvil.app/"
5. Type in any question about cryptocurrency and click "ASK"

**Using our website requires having the colab notebook connected to it at all times**. If no notebook is connected an error will appear. It is also not possible to have two notebooks connected to the server at one time.


## Tools ##

All of the tools we use are free to use. 
In order to use our app you need a google account. 
The google account is required to upload a notebook to [Google Colab](https://colab.research.google.com/). We also use [Google Drive](http://drive.google.com/) to permanently store the file for our annotated data (see Using our system, 1.)
To create our website we used [Anvil](https://anvil.works/). It is **NOT** required to have an Anvil account to use our website.


## Libraries ##

For our Question answering system a combination of libraries are required. All of these libraries are free to use and are automatically downloaded and installed in the google colab notebook. Libraries include:
- [Haystack](https://github.com/deepset-ai/haystack/) with these tools:
  - [PreProcessor](https://haystack.deepset.ai/usage/preprocessing)
  - [DocumentStore](https://haystack.deepset.ai/usage/document-store)
  - [Retriever](https://haystack.deepset.ai/usage/retriever)
  - [FARMReader](https://haystack.deepset.ai/usage/reader)
  - [Pipeline](https://haystack.deepset.ai/usage/pipelines)
- [Anvil Server](https://anvil.works/docs/uplink/quickstart)
