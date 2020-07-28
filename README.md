# PotterData
This is a data store for some data that I have been working with.

I only used a subset of characters from the Harry Potter books.  The relationships are *not* symmetric, e.g. Sirius Black likes his brother Regulus, but Regulus dislikes Sirius.  Positive scores mean a positive relationship, negative scores mean a negative relationship.

The characters.csv file contains a character id used for the relationship.csv file, a vague affiliation, and a general alignment (good, neutral, or bad).  While several of the characters could have multiple affiliations, I went with the one that the character was most strongly associated with for most of their 'screen time' in the book.  In addition, I wanted to distinguish between the students and adults, which is why we see Fred and George Weasley in "dumbledore's army."  The alignment is a general sense of whether the character wanted to help Harry (good) vs. Voldemort (bad), e.g. Regulus Black is neutral because he didn't even know about Harry even though he was working against Voldemort.

The relationship.csv file uses character id's with a relationship described by the table below.  The relationships are human-curated, so may have inconsisancies and typos.  I was more interested in including interesting graph structure than 100% consistancy and accuracy.  One important caveat is that these relationships come from the book, not inferred relationships that develop offscreen, e.g. while it is reasonable that over 7 years of mentoring Harry would be very close to McGonagle, they don't share enough scenes for such an implied relationship.  That is, most of McGonagle's mentoring appears 'off camera.'

1 - Acquaintances / Rivals

2 - Friends / Enemies

3 - Allies / Violent Hatred

4 - Family / Sworn Enemy

5 - Father-Son / Close Betrayal
