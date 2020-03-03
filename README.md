## Important

### NEW ! TEST YOUR EXAM-PRINTF WITH **[PFT_EXAM](https://github.com/cclaude42/PFT_EXAM)**

This is an edit of ft_printf tester PFT made by **[Gavin Fielder](https://github.com/gavinfielder)** to fit with 2019 rules.
This PFT only includes the 745 test combinations of the basic flags (%cspdiuxX% -0.*).
Tests were added to cover stars and null pointers.

**Your printf doesn't need to pass all the tests, some cover undefined behaviour (but it's better if it does).**

Original PFT : https://github.com/gavinfielder/pft

This update was made by **[cclaude](https://github.com/cclaude42)**

## Installation
**In the root of your ft_printf repo**, run :

```
git clone https://github.com/gavinfielder/pft.git pft_2019 && echo "pft_2019/" >> .gitignore && cd pft_2019 && rm unit_tests.c && rm options-config.ini && git clone https://github.com/cclaude42/PFT_2019.git temp && cp temp/unit_tests.c . && cp temp/options-config.ini . && rm -rf temp
```

## Usage

**Warning : everytime you change your printf, you need to** ```make re``` **in PFT again.**

**In the PFT_2019 repo**, run ```make re```

You can now run all the tests using ```./test``` 

To run only %s tests for example, you can use ```./test s```

To run tests #42 to #84, you can use ```./test 42 84```

## Credit
The code was written by [Gavin Fielder](https://github.com/gavinfielder). This is an update of the test file by [cclaude](https://github.com/cclaude42), with some tests removed and some added, for easier use with the 2019 printf subject.

Thanks to [lnezonde](https://github.com/leo125) and [macrespo](https://github.com/macrespo42) for their help debugging and their suggestions.
