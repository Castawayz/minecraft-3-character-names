All available 3 character/letter Minecraft names
=====

This is a small clojure script that queries the Minecraft API to test for all available 3 character names.

The found playernames are in *available-now.txt* (currently available names) and *soon-available.txt* (not currently in use but still under the 37 day protection.) Do note that these lists are NOT automatically updated, but instead show which names were available when the script was last run. If you've got a newer copy of these lists, feel free to submit a pull request.

The without-numbers files can be generated with
```
grep "^[a-z]*$" available-now.txt > available-now-without-numbers.txt
grep "^[a-z]*$" soon-available.txt > soon-available-without-numbers.txt
```
