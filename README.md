# StreamLit Node Display

This is a simple table displayed using Streamlit. It is a good starting point for creating more complex tables using Streamlit.

## Features

* Simple table
* Displayed using Streamlit

## Requirements

* Streamlit
* Python 3.7 or higher

## Getting Started

To get started, clone the repository and install the dependencies. Then, run the following command to start the app:
```
streamlit run app.py
```
## Table

The table is displayed using the `st.table` function. The function takes a list of lists as input, and displays the table in a tabular format.

## Example

The following code shows an example of how to use the `st.table` function:
```
data = [['Name', 'Age', 'Gender'],
['John Doe', 30, 'Male'],
['Jane Doe', 25, 'Female']]

st.table(data)
```

This code will display the following table:

Name | Age | Gender
------- | ----- | -----
John Doe | 30 | Male
Jane Doe | 25 | Female

## License

This project is licensed under the MIT License.

## Contact

If you have any questions or problems, please feel free to contact me on GitHub.

## Thanks
