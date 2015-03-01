# User-Dictionary
Hands on with the content provider of user Dictionary and getting the list of user saved words with their frequency


Things learnt

1. Content Providers - standard android content providers

2. Content URIS

3. Getting a content Resolver - using getContentResolver

4. Doing a query on the resolver- using resolver.query(CONTENT_URI,null,null,null,null) - this resolver talks to the content provider and talks to the database/data source

5. Simple Cursor Adapter to be initialized with the context of the app , layout of the textview of each listview item and the cursor to be used , the string array from which we get the columns to be mapped , to the int array of values to be assigned )
