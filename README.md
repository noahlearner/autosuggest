# autosuggest
This repo houses a fork of a colab built by Antoine Eripet at https://colab.research.google.com/drive/1xk5HYisMsdAy0ezZrpAQQX89Q5B8sP_q?usp=sharing.

## Welcome to the Autosuggest keyword tool.

This tool will create thousands of keywords for you to explore, along with Monthly search volumes for each one.

To use the tool:

1.   Open the [Google colab](https://colab.research.google.com/github/noahlearner/autosuggest/blob/main/Google_Suggestions.ipynb)
2.   **Enter your seed keyword**
3.   **Enter the country** you want to search in.
4.   **Enter your BigQuery Project ID**. If you haven't done so already, follow these steps to [create a project](https://cloud.google.com/resource-manager/docs/creating-managing-projects), and [turn on billing](https://support.google.com/googleapi/answer/6158867?hl=en).
5.   **Enter your BigQuery dataset**
6.   **Enter your BigQuery table**
7.   **Click Runtime > Run All** This will start the application which will take 1-5 minutes run.
8.   Watch the application run.  When it gets to the last step you'll need to authenticate as a verified Google user for your Google Cloud Project to allow the application to write the results to your BigQuery table.
