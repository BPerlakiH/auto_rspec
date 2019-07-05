# Automatically track file changes and launch rspec

Requires fswatch to be installed locally:
``brew install fswatch``

might need to make the bach file executable:
``chmod +X auto_test.sh``

next run it with:
``. auto_test.sh``

by default it will track the changes in the folders ``src`` and ``spec``
wich is the default after ``rspec --init``

save your changes in either folders (by editing your code or your tests) and the tests will launch
