## [Create a Giphy Search Engine](https://github.com/FEWDMaterials/UIReview/tree/master/p16)

Create a Giphy Search Engine using the Giphy API.


#### [API Docs](https://github.com/Giphy/GiphyAPI)

#### Requirements

1. Input field should handle `Enter` key press to initiate search
2. Submit button should also initiate search
3. Both search initiations should clear the input field
4. Top 10 results must be displayed in image form (this means you must process the data and then display them in image form)


#### Stretch Goals

1. Display a spinner while the api search is being completed
2. Disable the search button while api search is being completed
3. On initial load, display the trending gifs - these should disappear when user makes first search
4. Add a clear button to clear search
5. If user clears search, bring back the trending gifs
6. Build in 'pagination' - if more than 25 results are returned, display only the first 25. Add buttons that allow user to page through the other results by sets of 25.
7. Add optional rating checkboxes (ie: pg-13, r, etc). If a rating is selected, filter out results by rating
8. Build an **I'm Feeling Lucky** button that will generate one random Gif
9. Add an input field below the **I'm Feeling Lucky** button that contains the URL to the Gif. Do not let the user edit this input field. If possible, clicking on this input field will highlight the text (so user can easily copy and paste).
10. How would you extend the feature from #9 so that it is available to __all__ gif results?
