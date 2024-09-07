# sfmc-search-in-all-de
Search for a text string in all available Data Extensions and fields of type text

## How to use? 
1. deploy api.html as code snippet and get the url
2. Update the url value in index.html and deloy this as a landing page
3. Open the landing page and search for a string

    Note: These DEs will not be searched. Part of function - isValidDEToSearch.

        ["QueryStudioResults", "log", "ExpressionBuilderAttributes", "IGO_PROFILES", "IGO_VIEWS", "PI_SESSION_ENDS", "IGO_PURCHASES", "IGO_PRODUCTS", "IGO_PRODUCTATTRIBS", "PI_CONTENTVIEWS", "PI_CONTENT", "PI_CONTENTATTRIBS", "PI_SESSIONS", "Einstein_MC_Predictive_Scores", "PI_ABANDONED_CART_EVENT", "PI_ABANDONED_CART_ITEMS" ]

![How it looks](https://i.imgur.com/G5Ge9He.png)

## Future enhancments 
- [x] Make it async 
- [x] Add form 
- [ ] Add support to other field types (date, decimal)
