# test common values

Sometimes you need to compare multiple models, either by using random points or specific points to test suitability. It can be important to know after you perfrom an extract value to point what those values are. You can leverage field calculator to test if these models are outputting the same values to a point




Copy and paste the following code into the Calculate Field Code Block:
```rb
def common_test(l1,l2,l3):
    if l1 == l2 and l1 == l3 and l2 == l3:
        return l1
    else:
        return 0
```

<a href="https://www.buymeacoffee.com/sabioguitaS" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
