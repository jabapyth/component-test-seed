
# Two skeletons, really

This is the testing setup I use. The `add-skel` util copies over a test
directory, `component install`s mocha and chai, and adds a number of make
targets for testing.

This was made so that you can run `add-skel` *after* you've run `component
create`.

## Normal

    test/
    test/index.html
    test/karma.conf.js
    test/testem.json
    test/tests.js
    test/...various lib files

## Angular

    +
    test/test-e2e.js
    test/test-e2e-setup.js



