# PFT_2019
A PFT file to only tests mandatory 2019 ft_printf features

## Installation

First, you'll need to install PFT, by Gavin Fielder.

**In the root of your ft_printf repo**, run this:

```
git clone https://github.com/gavinfielder/pft.git pft && echo "pft/" >> .gitignore
cd pft
rm unit_tests.c
```

Then, you'll need to replace the unit_tests.c file you just deleted with the updated one.

**In the PFT repo**, run:
```
git clone https://github.com/YulonSil/PFT_2019.git temp_folder
cp temp_folder/unit_tests.c .
rm -rf temp_folder
```

Finally, you'll need to update the PFT script with the new units tests.
```
./enable-test
```
## Usage and credit

You can now run all the tests using ```./test```

To run only %s tests for example, you can use ```./test s```

To run tests #42 to #84, you can use ```./test 42 84```

For more info about PFT, visit https://github.com/gavinfielder/pft

**All credit goes to Gavin Fielder**
