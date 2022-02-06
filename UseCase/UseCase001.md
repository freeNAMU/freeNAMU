# UseCase001 Search Document
## Description
A reader search a document to view the document.

## Actor
 * Reader

## Precondition
None

## Success End Condition
The reader is taken to the desired document page.

## Failed End Condition
The reader gets a list of documents similar to the document titles entered.

## Main Scenario
1. A Reader enters document title at search bar in global navigator.
2. The system displays a list of documents similar to the document title entered by the reader.
3. The Reader select a document in the list.
4. The system displays the document.

## Alternative Scenario
3.
   1. If the reader press Enter when there is a document matching the entered document title:
      1. The system displays the document.
   2. If the document selected by the reader is a redirect document:
      1. The system displays the document to which the document refers.

## Exception Scenario
3. 
   1. If the reader presses Enter when no document matches the document title you entered:
      1. The system displays document not found page.