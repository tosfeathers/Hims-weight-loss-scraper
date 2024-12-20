# Hims Weight Loss Scraper

### This scraper uses Playwright to complete the Hims weight loss medication intake [form](https://www.hims.com/c/wm/introduction) and record which medication the website recommends. Information entered into the form is drawn from a pre-defined dictionary and can be easily changed in order to gather data about which medications the website recommends to different kinds of patients.

Note: This scraper worked as of 12/19/2024. However, the Hims website changes frequently, often adding/removing questions from the intake form. The scraper will need to be updated for any new questions added.

The first section of the jupyter notebook defines various functions for each page of the intake form.

The second section defines the patient_info dictionary. A list of dictionaries (representing different patients) can be passed through the scraper using a for loop. Changing an item in the dictionary changes the answer that will be selected on the respective page of the intake form.

The third section opens a headful Playwright browser, runs the scraper, and closes the browser.

