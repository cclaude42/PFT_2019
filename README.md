## Important
This is an edit of ft_printf tester PFT made by @gfielder to fit with 2019 rules.
This PFT only includes the 721 tests that a basic ft_printf should pass (%cspdiuxX% -0.*).

**Your printf should pass ALL the tests if you want to turn it in.**

Original PFT : https://github.com/gavinfielder/pft

This update was made by @cclaude

## Installation
**In the root of your ft_printf repo**, run :

```
git clone https://github.com/gavinfielder/pft.git pft_2019 && echo "pft_2019/" >> .gitignore && cd pft_2019 && rm unit_tests.c && git clone https://github.com/YulonSil/PFT_2019.git temp && cp temp/unit_tests.c . && rm -rf temp && ./enable-test
```

## Usage and credit
You can now run all the tests using ```./test``` 

To run only %s tests for example, you can use ```./test s```

To run tests #42 to #84, you can use ```./test 42 84```

**All credit goes to Gavin Fielder.** For more info about PFT, visit https://github.com/gavinfielder/pft
