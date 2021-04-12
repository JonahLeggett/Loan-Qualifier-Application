# Loan Qualifier Application

*This is a command line application to match applicants with qualifying loans. It will allow applicants to download results as a csv file so they can share their results in an Excel Spreadsheet*

---

## Technologies

This project leverages python 3.7 with the following packages:


* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* [pytest](https://docs.pytest.org/en/stable/) - For basic assertion testing of financial calculators and filters, and filio.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
pip install fire
pip install questionary
pip install pytest
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Loan Qualifier Prompts](Loan-Qualifier-Application/images/loan_qualifier.png)

Finally, choose a file path to save your csv containing your qualified loans and enter when prompted. 

---

## Contributors

Brought to you by Jonah A. Leggett. You can reach me at jonah.leggett@gmail.com 

You can add me at LinkedIn: (https://www.linkedin.com/in/jonah-l-29278a8a/)

---

## License

mit