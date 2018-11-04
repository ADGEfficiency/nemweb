The test in `test_nemweb.py` makes a new test database and checks that the data downloaded is the same as a previously run pickle - the problem is that CURRENT data is not persistent!  This means that either the pickle needs to be updated, or this test should be removed.

---

Dependencies = `pytest`

To run 
` $ cd nemweb/tests`
` $ pytest`
