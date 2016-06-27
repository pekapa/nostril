# Description
This is a Nose Wrapper to make it easy to test Python Packages from within Python.

This is done using the module instance or the module name with the following command:

    import nostril
    nostril.run('mypackage')  # Package name, you must be able to import mypackage
    nostril.run(mypackage)    # Or, if mypackage is already imported...


# Options
Alongside with the package name a serie of keyworded arguments can be passed, such as:
1. `cover=True` in order to include cover coverage to the tests.

  1.1. `html=True` in order to include coverage and output it to html.

  1.2. `xml=True` in orer to include coverage and output it to a xml file.

  1.3. `open_html=True` in order to include html and open the index.html in the end.


# How to install
As easy as `pip install nostril`
