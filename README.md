# AirLab Documentation
Public documentation for the <a href="http://theairlab.org/" target="_blank">AirLab</a> at Carnegie Mellon University. 

View live at 
<a href="https://theairlab.readthedocs.io" target="_blank">theairlab.readthedocs.io</a>.

## Contributing

The general commands are thus:
```bash
# install dependencies
pip install sphinx

# clone a copy
git clone git@github.com:castacks/AirLab-Documentation.git
cd AirLab-Documentation/

# make project changes under docs/source/

# build
cd docs/
make clean html

# preview changes by opening build/html/index.html in your browser

# commit build files
git commit -am "commit message"
# update online docs, takes several minutes to update
git push
```

The reStructuredText (`.rst`) files to edit are under `docs/source`. 
The sidebar's section headers and pages are defined in `docs/source/index.rst`.
To add a page, simply create a new `.rst` file and add it under the appropriate section in `index.rst`.


Feel free to contact Andrew for any questions.

## "Read the Docs" Management
The _Read the Docs_ dashboard is at https://readthedocs.org/projects/theairlab/. [Andrew Jong](http://theairlab.org/team/andrew_jong/) can provide access for your _Read the Docs_ account.
