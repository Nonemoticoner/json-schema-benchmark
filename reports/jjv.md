# `jjv` - test summary

# All validators fail these tests

some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part

remote ref, remote ref invalid

fragment within remote ref, remote fragment invalid

ref within remote ref, ref within ref invalid

change resolution scope, changed scope ref invalid

remote ref, remote ref valid

fragment within remote ref, remote fragment valid

ref within remote ref, ref within ref valid

change resolution scope, changed scope ref valid


# `jjv` failed tests

jjv failed the test &quot;valid definition, valid definition schema&quot;. Expected result: true but validator returned: false

jjv failed the test &quot;maxLength validation, two supplementary Unicode code points is long enough&quot;. Expected result: true but validator returned: false

jjv failed the test &quot;minLength validation, one supplementary Unicode code point is not long enough&quot;. Expected result: false but validator returned: true

jjv failed the test &quot;remote ref, containing refs itself, remote ref valid&quot;. Expected result: true but validator returned: false

**All other tests passed**.