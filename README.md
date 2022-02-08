# Different_languages_interface_testing
## Steps to check how it works:
<ul>
  <li>Clone project
  <li>Open terminal in project directory and enter "python install -r requirements.txt"
  <li>Check assertion with "pytest --language=en test_items.py"
  <li>Add "import time" and "time.sleep(30)" commands to the test_items.py
  <li>Open terminal in poject directory and enter "pytest --language=fr test_items.py"
  <li>See what happends
<ul>
