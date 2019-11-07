## Important
This is an edit of ft_printf tester PFT made by @gfielder to fit with 2019 ft_printf rules.
This PFT only includes the 721 tests that a basic 2019 ft_printf should pass (%cspdiuxX% -0.*) to make it easier to read.

Original PFT : https://github.com/gavinfielder/pft

This update was made by @cclaude

## Installation

First, you'll need to install PFT, by Gavin Fielder.
Then, you'll need to replace the unit_tests.c file you just deleted with the updated one.
Finally, you'll need to update the PFT script with the new units tests.

To do that, **run this in the root of your ft_printf repo**:

```
git clone https://github.com/gavinfielder/pft.git pft_2019 && echo "pft_2019/" >> .gitignore && cd pft_2019 && rm unit_tests.c && git clone https://github.com/YulonSil/PFT_2019.git temp && cp temp/unit_tests.c . && rm -rf temp && ./enable-test
```

## Usage and credit

You can now run all the tests using ```./test``` **Your printf should pass ALL the tests if you want to turn it in.

To run only %s tests for example, you can use ```./test s```

To run tests #42 to #84, you can use ```./test 42 84```

**All credit goes to Gavin Fielder.** For more info about PFT, visit https://github.com/gavinfielder/pft
