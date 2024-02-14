# CHANGE LOG:

## BUG 1:
- made parent div relative and made dropdown div absolute
- this allows the dropdown div to be on top of other content (simply changing position fixed will make other divs go down when the dropdown goes down)
- got rid of dropdown position styling as that moves the dropdown to a bad location

## BUG 2:
- put input inside label (main reason you cant change stuff)
- put setApproved before API call so there isnt a lag when you change stuff

## BUG 3:
- issue is that ALL EMPLOYEES option does not have an id
- gave it a -1 id and made sure to load all transactions if the id of selected item is -1

## BUG 4:
- fixed by concatting new response to previous response

## BUG 5:
- changed order of loading usestate so that it's set to true before the second api call

## BUG 6:
- fixed by making button display none when not paginated or when next page is null

## BUG 7:
- force page to fetch every time so data is always up to date