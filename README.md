Group: Aayan Lakhani

1. I would put my automated tests in 1: Within a Github action that runs whenever code is pushed. This way, the tests automatically run everytime code is pushed to make sure that whatever updates you made to the code didn't break functionality. If it did break it, you're able to go back and fix it before it gets out of hand.
2. I wouldn't use an E2E test to test function output, since that can be easily done with a unit test, since it doesn't rely on the complete user experience on the browser.
3. Navigation mode looks at the website during it's entire load process, while snapshot mode just looks at how the page is at the current moment, and doesn't look at how it changes.
4. Adding lang attributes to the HTML tags would make it more accessible for screen readers. Adding a meta description would help the site be more discoverable by search engines. Finally, making the cache lifetimes of certain assets like images would improve the performance of the site and make it load faster.
