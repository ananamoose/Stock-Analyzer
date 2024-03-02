# Stock Analyzer

This is a simple stock predictor, it will call an API to get raw financial data for a particular ticker, clean the data, calculate a feature value based on the financials, and predict the price based on that feature value. It will then show the model's results in graphical form. 

This is a high-level design and implementation meant to show my understanding of python, the libraries involved (such as pandas, sklearn, flask, and more), and other development topics like APIs.

To run the local project, first disable (as "no") or enable (as "yes") the API flag manually in app.py, since the API does have limits and can halt the program if limit is exceeded.

Then run "python app.py" and go to your local server.
