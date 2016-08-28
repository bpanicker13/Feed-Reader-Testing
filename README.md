## Udacity Front-End Nanodegree
# Feed-Reader Testing
____________________________
Jasmine is a behavior-driven development framework for testing JavaScript.
The thing I like the most is that it has clean syntax, and that makes writing tests easy.

```html
describe("A suite", function() {
  it("contains spec with an expectation", function() {
    expect(true).toBe(true);
  });
});
```

Instructions
------------
To view my testing app download all the files and open index.html in your browser. The key things I tested for are below.

RSS Feeds:
* all Feeds are Defined
* all Feed URL is not empty
* Feed names are not empty

The Menu:
* The menu is hidden by default
* When clicked the menu changes visibility

Initial Entries:
* Feed container has at least 1 entry

New Feed Selection:
* Feed content changes when new feed is selected

To view the demo on github pages go to https://bpanicker13.github.io/testing

