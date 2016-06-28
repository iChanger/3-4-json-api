# 3.4 JSON API Challenge

In the previous lesson we were saw that OMDb has search capability by using the `s` parameter, so as an assignment you will be practicing reading jQuery documentation and writing your own JavaScript to create a search for movies using this API.

Here are some hints of functions that you will need to use:

- [`$.click()`](http://api.jquery.com/click/) - This function allows you to specify what action will be taken when an element is clicked. So you'll have to make an API call with the search value whenever a button is clicked
- [`$.val()`](http://api.jquery.com/val/) - This function will get the current value from an `<input>` field. So use this inside of the click function.