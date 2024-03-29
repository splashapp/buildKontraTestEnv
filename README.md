### KONTRA Test Environment
buildKontraTestEnv project is used to setup a standarized KONTRA Test environment with an installed KONTRA release, database (e.g. DB2) and standarized tools to execute test cases/suites. The tester can use the KONTRA Test Environmet to:

- Test KONTRA in a defined test environment with different KONTRA products (e.g. Kreditkartenabrechnung)
- Test KONTRA with a defined KONTRA product but different KONTRA releases
  1. KONTRA releases
  2. KONTRA database releases
- Test KONTRA with a defined KONTRA product but different test environments  
  1. Platforms/hardware (e.g. xxx (linux), macbook pro (macOS))
  2. Databases (e.g. DB2, Oracle)

The standard test environment (out of the box) consist out of:
  1. KONTRA release: x.xxx
  2. Database release: x.xxx
  3. Platforms/hardware: dependent on local machine (tested with macbook pro (macOS))
  4. Database: DB2 


A detailed description of the manual steps is here: https://github.com/splashapp/buildKontraTestEnv/tree/master/doc/KONTRA 