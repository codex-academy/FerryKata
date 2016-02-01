## Part 2

Once you can load cars into the Ferry, look at other things the Ferry company is interested in:

* knowing how many cars of a certain color are on the Ferry;
* updating the people and car counts correctly when a car leaves the Ferry;
* giving a car 50% discount after three trips on the same ferry. The board method should return 'half price!';
* giving a free trip after 7 trips on any Ferry. The board method should return 'you go free!'

## Code Coverage

Code coverage tells you how much of your code is covered by your tests. Higher code coverage can mean your code has a good chance of being well-tested and contain few bugs.

Let's use a tool called [Instanbul](https://gotwarlost.github.io/istanbul/) to check our code coverage.

### Istanbul

Install Istanbul globally like this:

```
$ npm install -g istanbul
```

To run Istanbul's coverage calculation with your mocha tests, run:

```
istanbul cover _mocha
```

Instanbul generates a web page of the detailed results of its calculations to `coverage/lcov-report/index.html`. Look at this page to see which particular bits of your code aren't being covered by your tests.
