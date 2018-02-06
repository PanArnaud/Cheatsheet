### Launch all test for a bundle (MyBundle)
`php phpunit-5.7.17.phar -c app src/MyBundle/`

### To get more details
Add `--debug`

### SQLSTATE[08004] [1040] Too many connections
Add `--process-isolation` to isolate each test into a new php process.
