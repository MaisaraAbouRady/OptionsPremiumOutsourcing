# Options Premium Outsourcing
## Technical Interview Task

### What is this repo?

In this repository, I present the working files of an interview task to work for a client of Options Premium Outsourcing, so as for them to see the work details as well as the outcome.

The actual website can be found on: http://options.epizy.com/

### Disclaimer

- The hosting service doesn't support CI to automate server deployemnt in sync with github merges.
- The original web page to clone was not based on a responsive web design grid or technique. In order to keep the task consistent, I've only utilized CSS Media Queries to add **some** responsiveness and screen-size compatibility. However, that's not the best responsiveness we can get.
- The logo has been positioned at the left, aliging with the width of the `contentColumn` `div`, following the same standards applied on the original certainlyhome.com website.

### Screen-size Compatibility

All page elements are already responsive as the `contentColumn` `div` has a maximum width and is included in a relatively positioned `wrapper` `div`, except for the logo. The dimensions of the logo are fixed, which is not quite convenient for small screens.

### PageSpeed Insights

- All photos have been optimized and compressed.
- Tested the efficiency of `rocket-loader` script:

> |         Parameter         | With | Without |
> |:-------------------------:|:----:|:-------:|
> | First Contentful Painting | 0.8s |   1.0s  |
> |        Speed Index        | 0.9s |   1.6s  | 

