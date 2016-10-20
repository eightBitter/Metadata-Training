Schema.org Training Session Two, Exercise Instructions
======================================================

This session will be broken up into two exercises. The main focus will be Exercise 1. If you get through the first exercise with time to spare, move on to Exercise 2.

See the resource list at the bottom for helpful resources.

Exercise 1
----------

In this exercise you will be converting a spreadsheet of data into Schema/JSON-LD. Open up the *schema_library* spreadsheet. Download and open *template.jsonld* using a text editor. Save the template as (a new file) *library.jsonld*.

Using the [Schema.org page for Library](http://schema.org/Library), convert the spreadsheet data over to the new JSON-LD file. Each column in the spread translates to a property in Schema.org. Not all lines in the template will necessarily be used; it’s just a template. At the bottom of the Schema.org page you will see a JSON-LD example record. This will give you some guidance.

There maybe be more than one entity type to convert over. Hint: you will probably need to create an embedded object (there’s an example of this in the template).

If you want to make sure your JSON-LD code is valid, copy and paste the code into the [JSON Validator](http://jsonlint.com/). This will tell you if the JSON formatting is correct. However, it won’t give feedback on the meaning behind the data (the validator won’t yell at you if you say Hunt Library is a Person).

If you want to better understand the meaning behind the data, copy and paste your code into the [Google Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool). Don’t worry if you receive any error messages. This is just Google’s interpretation of the data.

Once you are done converting the data over, save the JSON-LD file, and email the file to [the facilitator].

Exercise 2
----------

This exercise will be freestyle. Using the [Schema.org page for Person](http://schema.org/Person), create a record for yourself using the *template.jsonld*. Save this file as *[yourFirstName].jsonld* (ex. *jacob.jsonld*). You can describe yourself in whatever way you like, using any of the acceptable properties from Schema.org.

Feel free to explore the formatting and data with the tools listed above.

Once you are finished, save the file, and email the file to [the facilitator].

Resource List
-------------

- [Schema.org - Library](http://schema.org/Library)
- [Schema.org - Person](http://schema.org/Person)
- [Presentation from Part One](../session-one)
- [JSON Validator](http://jsonlint.com/)
- [Google Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool)
- [Google Knowledge Graph](https://developers.google.com/knowledge-graph/) Search Result (only functions if you put in your own API Key)
  - https://kgsearch.googleapis.com/v1/entities:search?query=james+b+hunt+jr+library&key=API_KEY&limit=1&indent=True
