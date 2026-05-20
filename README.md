Group: Aayan Lakhani

1. I would put my automated tests in 1: Within a Github action that runs whenever code is pushed. This way, the tests automatically run everytime code is pushed to make sure that whatever updates you made to the code didn't break functionality. If it did break it, you're able to go back and fix it before it gets out of hand.
2. I wouldn't use an E2E test to test function output, since that can be easily done with a unit test, since it doesn't rely on the complete user experience on the browser.
