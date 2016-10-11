# Home++
This is my homepage!

If you would like a copy already preloaded with some sites, download [home++.html](https://raw.githubusercontent.com/dospunk/homeplusplus/master/home%2B%2B.html). For a blank version, download [home++b.html](https://raw.githubusercontent.com/dospunk/homeplusplus/master/home%2B%2Bb.html).

Here's a pretty basic rundown of how it works (so you don't have to read my probably horribly formatted code)

1. It goes through each item in each key in the plaes object and aadds the first item in the array (the name of the link) to the input field's datalist

2. When you input text it checks the first character against each key in the places object. Once it finds the correct key it checks the input against each name in the array. This way the program doesn't have to go through every single item every time.

3. Once it finds the matching name, it redirects you to the url that corresponds to that name
